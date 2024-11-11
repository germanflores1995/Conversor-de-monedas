<h1>💰CONVERSOR DE MONEDAS EN JAVA☕💻</h1>

# ✨Descripción 
Este es un conversor de monedas desarrollado en Java que utiliza una API para obtener tasas de cambio en tiempo real. Permite convertir diferentes monedas de manera sencilla.🌍💵

## 🔑Características
- 🌐Conversión de múltiples monedas.
- 📊Uso de una API externa para obtener tasas de cambio en tiempo real.
- 💱Soporte para monedas como USD, ARS, COP, etc.

## ⚙️Requisitos
- ☕Java 11 o superior.
- 🔧Maven o Gradle (para la gestión de dependencias).
- 🌍Una cuenta de API de conversión de monedas  (exchangerate-api.com](https://www.exchangerate-api.com).

## 🛠️Instalación
1.Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/conversor-de-monedas-java.git
```
2.Navega al directorio del proyecto:
  ```bash
  cd conversor-de-monedas-java
  ```
3.Agrega tu clave de API en el archivo config.properties(o donde corresponda).

4.Compila e instala las dependencias:
```bash
  mvn install
```
5.Ejecuta el proyecto:
```bash
  mvn exec:java
```  
Nota: Asegúrese de obtener una clave de API válida para las tasas de cambio de moneda.

## 📊Uso
Para utilizar el conversor de monedas, ingresa el monto y selecciona las monedas de origen y destino. El sistema obtendrá las tasas de cambio desde la API y realizará la conversión.

Ejemplo de uso:
```bash
Ingrese la cantidad a convertir: 100
  1)Dolar ==> Peso Argentino.
  2)Peso Argentino ==> Dolar.
  3)Dolar ==> Real Brasileño.
  4)Real Brasileño ==> Dolar.
  5)Dolar ==> Peso Colombiano.
  6)Peso Colombiano ==> Dolar.
  7)Salir.
  Resultado: 100 USD = 99725 ARS
```

## 🌍API Utilizada
Este proyecto utiliza la API de [exchangerate-api.com](https://www.exchangerate-api.com) para obtener tasas de cambio en tiempo real.

Para utilizar la API, regístrate en su sitio web y obtén una clave API gratuita.

## 📬Contacto
Si tienes alguna pregunta, puedes contactarme en germanflores1995@gmail.com

