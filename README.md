# Blackridge Ventures LLC Website

Static business website for Blackridge Ventures LLC built with plain HTML and CSS.

## Project Structure

```text
blackridge-website/
├── index.html
├── about.html
├── contact.html
├── css/
│   └── styles.css
└── README.md
```

## Local Preview

Open `index.html` in your browser to preview the site locally.

## Deploy to Netlify

### Option 1: Manual Deploy

1. Sign in to [Netlify](https://www.netlify.com/).
2. Select **Add new site** > **Deploy manually**.
3. Drag and drop the `blackridge-website` folder into the upload area.

### Option 2: Deploy from Git

1. Push this project to a Git provider (GitHub, GitLab, or Bitbucket).
2. In Netlify, select **Add new site** > **Import an existing project**.
3. Connect your repository and choose this project.
4. Use the following settings:
   - Build command: *(leave blank)*
   - Publish directory: `.`
5. Click **Deploy site**.

## Notes

- This is a fully static site.
- No Node.js, build pipeline, or framework is required.
