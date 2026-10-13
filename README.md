

# My Cloud & Web Portfolio

A beginner-friendly portfolio website built using native HTML,
CSS and JavaScript.

## Features

- Responsive layout for desktop and mobile devices
- Semantic HTML and basic accessibility features
- No external libraries or API keys
- Automatic copyright year
- Git version control
- Planned deployment to Azure Static Web Apps

## Requirements

- A modern web browser
- A text editor, such as Visual Studio Code
- Git for version control

## Run locally

Open `index.html` in your browser.

Alternatively, from the project directory, run:

    python3 -m http.server 8000

Then visit:

    http://localhost:8000

Stop the local server with Ctrl+C in the terminal.

## Project structure

- index.html: page structure and content
- css/style.css: layout and visual styles
- js/script.js: JavaScript behavior
- README.md: project documentation

## Security

This project does not contain API keys, passwords,
or external dependencies.

## Learning status

Educational project. The Azure deployment will be completed
after local testing and repository setup.



============================================================
SERVIDOR LOCAL PYTHON:
============================================================

python3 -m http.server 8000

Rodar no diretorio do projeto web!

===========================================================
TESTE:

curl -I http://localhost:8000/
curl -I http://localhost:8000/css/style.css
curl -I http://localhost:8000/js/script.js


test -f index.html && echo "OK: HTML encontrado"
test -f css/style.css && echo "OK: CSS encontrado"
test -f js/script.js && echo "OK: JavaScript encontrado"
test -f README.md && echo "OK: documentação encontrada"

grep -nE 'stylesheet|script src|current-year|id="main"' index.html