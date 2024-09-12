## This is a reproduction of an issue I had with SCSS and Next.js.

> For an unknown reason with scss when using a local svg file with compiled sprites as background the svg is not rendered correctly.

# How to reproduce

1. Clone the repo
2. Install dependencies
3. CD into `./nextjs` Run the dev server
4. Open the browser at http://localhost:3000
5. Go to the `src/app/page.tsx` file
6. Comment out the import of the css file and uncomment the import of the scss file
7. You will notice that the svg is **not** rendered when using the scss file but it is rendered when using the css file

8. Go back to root and cd into `./react-example` and run the dev server
9. both scss and css files are rendered correctly
