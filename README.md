# Seguimiento de Pacientes Veterinaria

Aplicación de gestión de pacientes para veterinaria construida con **React**, **TypeScript**, **Zustand** para manejo de estado global y **React Toastify** para notificaciones.

## Características

- Añadir, editar y eliminar pacientes.
- Persistencia de datos en localStorage usando Zustand + persist.
- Formularios validados con React Hook Form.
- Notificaciones visuales con React Toastify.
- Estilos modernos con Tailwind CSS.

## Tecnologías principales

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction) (manejo de estado global)
- [React Toastify](https://fkhadra.github.io/react-toastify/introduction) (notificaciones)
- [React Hook Form](https://react-hook-form.com/)
- [Tailwind CSS](https://tailwindcss.com/)

## Scripts

- `npm run dev` — Inicia el servidor de desarrollo.
- `npm run build` — Compila la aplicación para producción.

## Instalación

1. Clona el repositorio.
2. Instala las dependencias:

   ```bash
   npm install
   ```

3. Inicia el servidor de desarrollo:

  ```bash
   npm run dev
  ```

## Estructura principal
- `src/store.ts:` Estado global con Zustand y persistencia.
- `src/components/PatientForm.tsx:` Formulario de pacientes.
- `src/components/PatientsList.tsx:` Listado de pacientes.
- `src/App.tsx:` Composición principal de la app.

## Notas 

- El estado de pacientes se maneja en `src/store.ts` usando Zustand y se persiste automáticamente en localStorage.
- Las notificaciones de éxito y error se muestran usando React Toastify, importado y configurado en `src/App.tsx.`

---

¡Clona este repositorio y comienza a gestionar tus pacientes veterinarios de forma eficiente y organizada!