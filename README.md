- from iqoptionapi.stable_api import IQ_Option

# Crear una instancia de la API de IQ Option
iq_api = IQ_Option("email", "password")
iq_api.connect()

# Obtener información de la cuenta
balance = iq_api.get_balance()
print("Saldo actual:", balance)

# Obtener lista de activos disponibles
activos = iq_api.get_all_open_time()
print("Activos disponibles:", activos)

# Realizar una operación de compra de prueba (reemplazar con los parámetros reales)
instrumento = "EURUSD"
monto = 1
accion = "call"  # o "put" para una opción de venta
resultado, id_opcion = iq_api.buy(monto, instrumento, accion)
print("Operación realizada:", resultado)

# Desconectar la API
iq_api.close_connection()
👋 Hi, I’m @yuni1992
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
yuni1992/yuni1992 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
