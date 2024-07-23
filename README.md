# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

```bash
npm create vite@latest ton-web -- --template react-ts
npm install @ton/ton @ton/core @ton/crypto
npm install @orbs-network/ton-access
npm install vite-plugin-node-polyfills
npm install @tonconnect/ui-react
npm run build
npm run deploy
# NOTE: after deploy create public/tonconnect-manifest.json file with your app info then copy https://kiyoshitaro.github.io/ton-web/tonconnect-manifest.json to manifest in main.tsx
import '@twa-dev/sdk'; # in App.tsx to public webapp as TWA in telegram

# Select "Bot Settings" and then select "Menu Button". Now select "Configure menu button" to edit the URL and type your published website URL

```