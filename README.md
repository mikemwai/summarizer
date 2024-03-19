# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- Build the app:

```sh
    npm run build
``` 

- Run the app:

```sh
    npm run dev
``` 

`N\B:` Before building or running the app, create a `.env` file at the project root folder and add the API key for the [article summarizer](https://rapidapi.com/restyler/api/article-extractor-and-summarizer?utm_source=youtube.com%2FJavaScriptMastery&utm_medium=referral&utm_campaign=DevRel) from [Rapid API](https://rapidapi.com/hub).

- How the `.env` file should look like:

```sh
    VITE_RAPID_API_ARTICLE_KEY = 
```
