#how to set up tailwind css

#step1: use this following commands
```
npm install -D tailwindcss
npx tailwindcss init

```
#step2: update tailwind.config.js file to include this line
```
  content: ["./src/**/*.{html,js}"],

```
#step3: create src/input.css to include
```
@tailwind base;
@tailwind components;
@tailwind utilities;

```
#step4:include src/output.css file to your html

#step5: run the following command
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

or npm run build  

       //command use as we make a shortcut in json file in scripts
```