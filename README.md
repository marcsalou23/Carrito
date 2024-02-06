# Carrito 

## Descripción

La aplicación es una tienda en línea que muestra productos y permite a los usuarios agregar productos al carrito de compras.

## Estructura de Archivos

El código fuente de la aplicación está organizado de la siguiente manera:

- **components/**: Contiene los componentes de React utilizados en la aplicación.
- **context/**: Contiene el contexto de React utilizado para administrar el estado del carrito de compras.
- **hooks/**: Contiene los hooks personalizados utilizados en la aplicación.
- **mocks/**: Contiene datos de prueba en formato JSON.
- **config.js**: Archivo de configuración que contiene variables de entorno y configuraciones.
- **App.jsx**: Archivo principal que define la estructura y el comportamiento de la aplicación.

## Componentes Principales

- **Header.jsx**: Componente de encabezado que muestra el encabezado de la aplicación.
- **Footer.jsx**: Componente de pie de página que se muestra solo en entornos de desarrollo.
- **Products.jsx**: Componente que muestra la lista de productos disponibles.
- **Cart.jsx**: Componente que muestra el carrito de compras y permite agregar productos.

## Funcionalidades Principales

- **Filtrado de Productos**: Los productos pueden ser filtrados según ciertos criterios.
- **Agregar al Carrito**: Los usuarios pueden agregar productos al carrito de compras.
- **Contexto de Carrito**: Se utiliza un contexto de React para administrar el estado del carrito de compras en toda la aplicación.

## Configuración y Desarrollo

La aplicación utiliza una variable de entorno `IS_DEVELOPMENT` para determinar si se muestra el pie de página en entornos de desarrollo. Esta variable se define en el archivo `config.js`.

## Uso

Para utilizar la aplicación, sigue los siguientes pasos:

1. Clona el repositorio en tu máquina local.
2. Instala las dependencias utilizando npm o yarn.
3. Ejecuta la aplicación utilizando un entorno de desarrollo.

```bash
npm install
npm start
```

## Notas

Esta aplicación es un proyecto de ejemplo y puede ser extendida para incluir más características y funcionalidades.

---

