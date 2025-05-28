# React Typescript Template

Esta es una plantilla base para iniciar un proyecto con React y TypeScript.

Está pensada para desarrolladores que desean comenzar con una configuración mínima pero profesional, incluyendo ESLint, Prettier y una suite de tests preconfigurada con Vitest y Testing Library.


---

## Tecnologías incluidas

- ⚛️ **React** con **TypeScript**
- 🛠 **Vite** como bundler ultra rápido
- 🎨 **CSS Modules** para estilos encapsulados
- ♿ **ESLint** (v9) con `jsx-a11y` para accesibilidad
- ✨ **Prettier** para formateo automático de código
- 🧱 Estructura de carpetas profesional y modular
- 🧹 Reset global de estilos (`global.css`)
- ⚙️ Listo para testeo y ampliación futura (GraphQL, Zustand, etc.)
- 🧠 Devlog para ir tomando apuntes a medida que desarrollas

---

## Estructura del proyecto

```txt
src/
├── App/
│   └── App.tsx
│   └── App.test.tsx
│   └── main.tsx
├── features/
├── shared/
│   └── constants
│   └── hooks
│   └── services
│   └── types
│   └── ui
│   └── utils
├── styles
│   └── global.css
├── tests
│   └── setupTests.ts
```
## Forma de uso

Introduce los siguientes comandos con el nombre de tu proyecto, entrea en él e instala las dependencias:

```
npx degit ivanmartinez777/react-typescript-template my-new-project
cd my-new-project
npm install
npm run dev
```