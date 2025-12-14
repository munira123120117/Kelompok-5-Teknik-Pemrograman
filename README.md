st.set_page_config(page_title="Pemetaan Gravity", layout="wide")
st.title("Aplikasi Desain Pemetaan Gravity!")
st.markdown("Masukan data pada sidebar untuk membuat peta kontur")

st.markdown(
    """
Upload data survei berisi kolom X, Y, dan value (misalnya anomali magnetik atau bouguer anomaly).
Aplikasi akan membuat grid interpolasi dan menampilkan peta heatmap serta kontur
"""
)
