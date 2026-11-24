# Public frontend repository

1. Create a public GitHub repository named `Retruns` and push the contents of this `Frontend/` folder to its `main` branch. That preserves the URL `https://mirnasir007.github.io/Retruns/`.
2. In repository Settings → Pages, choose GitHub Actions as the deployment source.
3. After the Render backend is deployed, replace the placeholder in `config.js` with its exact HTTPS URL.
4. Push the config change to `main`; the workflow publishes `index.html` and `config.js`.

The site and browser code are public and inspectable. The full-access password is checked by the backend, not stored in this repository. GitHub Pages support for private repositories depends on the GitHub account plan; this setup expects a public frontend repository.
