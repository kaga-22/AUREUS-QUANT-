# Aureus Quant

A React single-page project built with Vite. Its sections are separate navigable pages, and the shared terminal and calculator interactions are rendered with React.

## Run locally

1. Install Node.js 20 or newer.
2. Run `npm ci`.
3. Run `npm run dev` and open the local URL printed by Vite.
4. Run `npm run build` to create the production site in `dist`.

## Publish a shareable GitHub Pages link

1. Create a **public** GitHub repository and upload/push the contents of this folder to its `main` branch.
2. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
3. Open the **Actions** tab and wait for **Deploy React site to GitHub Pages** to finish successfully.
4. GitHub will show the public URL on the Pages settings page. It will usually be `https://OWNER.github.io/REPOSITORY/`.
5. Share that URL with your boss. To let people propose changes, invite them in **Settings → Collaborators** or have them fork the public repo and open pull requests.

The included workflow redeploys the site whenever changes are pushed to `main`. The **Collaborate** page links to the repository used by that workflow.

## Project notes

- The market ticker and terminal are browser-side simulations; they do not connect to a broker or provide real-time quotes.
- The calculator is hypothetical and does not guarantee returns.
- This static site has no payment, account creation, or trading backend.
- Before sharing performance or financial information, make sure supporting evidence and disclosures are available and current.

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the suggested collaboration workflow.
