# Gigapixel — deployment

Static Astro site. No server needed. To publish:

## 1. Upload to a GitHub repository
Create a new (private) repository on GitHub, then **Add file -> Upload files**
and drag in EVERYTHING from this folder. `package.json` must sit at the repo
root, not inside a sub-folder. Commit.

## 2. Connect Netlify
app.netlify.com -> Add new site -> Import an existing project -> GitHub ->
pick the repo. Settings auto-detect from `netlify.toml`:
- Build command: `npm run build`
- Publish directory: `dist`
Click Deploy (first build ~1-2 min). Rename the auto-generated *.netlify.app
address under Site configuration if you like.

## 3. Contact form (one-time activation)
The first message sent through the form triggers an activation email to
gigapixel.by@gmail.com. Click the link once; after that every enquiry and any
attached files land in that inbox.
