# 📈 Crypto Query - Cotizador de Criptomonedas

Una herramienta potente y rápida para obtener cotizaciones en tiempo real de las criptomonedas más importantes del mercado frente a diversas divisas internacionales.


## 🔍 ¿Qué hace esta aplicación?

Esta app se conecta a una API externa para obtener el valor actual del mercado cripto. El usuario selecciona su moneda local y la criptomoneda de su interés, y la aplicación genera un reporte detallado con el precio más alto, el más bajo y la variación de las últimas 24 horas.

## ✨ Funcionalidades Principales

- **Cotización en Tiempo Real:** Datos actualizados al instante mediante el consumo de la API de [CryptoCompare](https://min-api.cryptocompare.com/).
- **Validación de Formularios:** Sistema de alertas para asegurar que ambos campos (Moneda y Cripto) estén seleccionados.
- **Detalle Exhaustivo:** Muestra información crítica como:
  - Precio actual.
  - Precio más alto y más bajo del día.
  - Variación porcentual en las últimas 24 horas.
  - Última actualización del precio.
- **Experiencia de Usuario (UX):** Incluye un *Spinner* de carga para indicar que la petición a la API está en proceso.
- **Diseño Responsivo:** Interfaz moderna y adaptable construida con styled-components o CSS modular.

## 🛠️ Stack Tecnológico

- **React.js**: Biblioteca base para la UI.
- **Styled Components**: Para un CSS dinámico y encapsulado dentro de los componentes.
- **Hooks Personalizados (Custom Hooks)**: Creación de hooks reutilizables para el manejo de los selectores.
- **Async/Await & Fetch**: Para una gestión limpia de las peticiones asíncronas.

## 🚀 Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/rjracer007/cripto-app.git](https://github.com/rjracer007/cripto-app.git)
