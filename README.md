# BetterDiscordFix
Commands that I needed to run for BetterDiscord to actually install instead of just breaking
Dependencies: Git, Node.js
https://git-scm.com/downloads
https://nodejs.org/en/download/

Discord must be open

```
git clone https://github.com/BetterDiscord/BetterDiscord.git
cd BetterDiscord
npm install -g pnpm
npm i
npm i circular-dependency-plugin
npm i babel-loader
npm i babel-plugin-module-resolver
npm i @babel/preset-react
npm i @babel/preset-env
npm i css-loader
npm i postcss-loader
npm i postcss-easy-import
pnpm build
pnpm inject
```
