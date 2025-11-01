I'm going to set up Tailwind CSS step by step. Here's the complete process:

Step 1: Install Tailwind CSS
npm install -D tailwindcss

Step 2: Create tailwind.config.js
Create the file in your current working directory:
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

Step 3: Create directory structure
mkdir src

Step 4: Create input.css
Create src/input.css with:
@tailwind base;
@tailwind components;
@tailwind utilities;

Step 5: Run Tailwind CLI
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

Step 6: Use Tailwind in your HTML
Create an HTML file in your src directory and link to the generated CSS:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tailwind CSS Project</title>
    <link href="output.css" rel="stylesheet">
</head>
<body>
    <div class="bg-blue-500 text-white p-4">
        <h1 class="text-2xl font-bold">Hello Tailwind!</h1>
        <p class="mt-2">Tailwind CSS is working!</p>
    </div>
</body>
</html>

Important Notes:
Keep the CLI running - The --watch flag means Tailwind will automatically rebuild when you make changes to your templates

File structure should look like this:
your-project/
├── tailwind.config.js
├── src/
│   ├── input.css
│   ├── output.css (generated)
│   └── index.html

The setup is now complete You can start using Tailwind CSS classes in your HTML files. The CLI will watch for changes and rebuild the CSS automatically.
