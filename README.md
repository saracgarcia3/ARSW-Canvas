# 🎨​ ARSW-Canvas - Real-time Drawing with WebSocket

## Descripción

Este proyecto es una aplicación web desarrollada con **Spring Boot** y **WebSocket** para permitir la sincronización en tiempo real de un lienzo de dibujo en el navegador. Los usuarios pueden dibujar en un lienzo (usando p5.js) y sus dibujos se sincronizan en tiempo real en todas las pestañas abiertas.

## 📝​Funcionalidades:
- Dibuja en el lienzo con el mouse.
- Sincronización en tiempo real entre todas las pestañas del navegador usando WebSocket.
- Opción para borrar el lienzo en todas las pestañas a la vez mediante un botón "Clear Board".

## 👩🏼‍💻​Tecnologías

- **Backend**: Spring Boot, WebSocket
- **Frontend**: HTML, JavaScript (p5.js para el lienzo de dibujo)
- **Dependencias**:
  - `spring-boot-starter-websocket`
  - `spring-boot-starter-web`
  - `p5.js` para el lienzo interactivo

## ▶️​ Instalación

1. Compilar el proyecto:
    ```bash
    mvn clean install
    ```

2. Se ejecuta el servidor:
    ```bash
    mvn spring-boot:run
    ```

5. Se abre el navegador y se accede a la aplicación en:
    - `http://localhost:8080/status` para verificar que el servidor está corriendo.
    - `http://localhost:8080/index.html` para interactuar con el lienzo de dibujo.

## ✅​ Uso

- **Dibuja en el lienzo**: Haz clic y arrastra el mouse para dibujar.
- **Sincronización en tiempo real**: Los dibujos realizados en una pestaña se sincronizan automáticamente en las demás.
- **Borrar el lienzo**: Haz clic en el botón "Clear Board" para borrar el lienzo en todas las pestañas.

<p align="center">
<img width="868" height="561" alt="image" src="https://github.com/user-attachments/assets/6e5c009b-db2d-4178-aa82-24d42ed30110" />
</p>

- Video de la funcionalidad:  https://www.loom.com/share/48c7e4fa8df14f2f9b88663cd55375c8?sid=859fa254-8a2f-4d47-860b-83079caefc52
