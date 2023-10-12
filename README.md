
npm create vite@latest .

✔ Select a framework: › React
✔ Select a variant: › TypeScript

npm install
npm run dev


folder structure:
- assets
    - css
    - fonts 
    - images
- components 
    - Button
        - Button.tsx
        - button.module.css
        - Button.test.ts
    - index.ts ()
- utils
- views
    - about 
        - components `./src/views/about/components` держит компоненты, которые используются только в пределах определенной вьюхи.
- hooks
- services
- store
    - about 
        - actions
        - initial-state.ts
        - reducers.ts
        - saga.ts
        - selector.ts

root dir:
- jsonconfig.json

[https://github.com/ults-io/vscode-react-javascript-snippets/blob/HEAD/docs/Snippets.md](snippets list)