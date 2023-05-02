# Amplify bundle size demo

Demo of bundle size when using a single hook &amp; provider

Based on Vite React Typescript template. To compute bundle size, just run `npm run build`

## Before installing amplify-ui
 
Bundle size is 146kb, most of that React DOM

- Treemap: https://real-sealion.static.app/treemap
- Sunburst: https://real-sealion.static.app/sunburst

## After installing amplify-ui 

With the `<Authenticator.Provider>` provider and the `useAuthenticator()` hook, bundle size is 1.52MB 

- Treemap: https://real-sealion.static.app/treemap692
- Sunburst: https://real-sealion.static.app/sunburst10
