# Portfolio of Utkarsh Payal

<img src ="https://utkarsh-payal.me/main.png" />

This is my website to introduce myself, here I put my skills, portfolio, and contact details.

This project was created with CRA (Create React App) using TypeScript.

## Features

- **Single-page layout** with smooth-scrolling navigation (React Router + `react-router-hash-link`) to the Home, About, Projects and Contact sections.
- **Hero** section with social links (LinkedIn, GitHub, Telegram) and a contact button.
- **About** section with a short bio and main skills (React, HTML, CSS, JavaScript).
- **Projects** section with cards linking to GitHub repositories, animated on scroll (`react-animate-on-scroll`).
- **Contact form** powered by [Formspree](https://formspree.io/) (`@formspree/react`), with email validation (`validator`) and toast notifications (`react-toastify`).
- **Light/dark theme toggle** and a **resume download** button in the header.
- Animated particle background (`react-tsparticles`).
- Footer with social links.

## Technologies used:
- React
- Typescript
- Styled Components

## Getting started

Prerequisites: Node.js and npm.

```sh
npm install
npm start
```

The development server runs at http://localhost:3000.

### Available scripts

| Command | Description |
| ------- | ----------- |
| `npm start` | Run the app in development mode |
| `npm run build` | Create a production build in `build/` |
| `npm test` | Run the CRA (Jest) test runner (no test files are currently included) |
| `npm run eject` | Eject from Create React App (irreversible) |

## Configuration

No environment variables are used. The Formspree form ID is set directly in `src/components/Form/Form.tsx` (`useForm(...)`); replace it with your own Formspree form ID if you fork this project.

## Project structure

```
public/            # index.html, sitemap.xml, images
src/
  App.tsx          # Header, Main, Footer
  components/      # About, Contact, Footer, Form, Header, Hero, Main, Project
  styles/global.ts # global styled-components styles (incl. light theme)
  assets/          # icons, images, resume PDF
```
