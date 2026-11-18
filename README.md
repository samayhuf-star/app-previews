# app-previews
Built web previews of the apps. Each app lives in its own folder and is served at
`https://samayhuf-star.github.io/app-previews/<app>/`.

Run the **Build web preview** workflow (Actions tab) with the source repo, branch and folder name.
Private source repos need an Actions secret named `PREVIEWS_TOKEN` (a token with read access to them).
