# my.jsonresume
* This is current my CV / resume
* It's written in JSON resume schema: https://github.com/jsonresume/resume-schema

## How to preview resume with theme
* pre-req: node.js / npm, resume-cli https://github.com/jsonresume/resume-cli
* npm install: `npm install -g resume-cli`
* run: `resume serve --theme <theme>`
* e.g: `resume serve --theme slick`

### JSON resume themes
* https://jsonresume.org/themes/

## How to generate resume in other formats
* if you want to use specific theme you need to install that theme 1st: `npm install -g jsonresume-theme-slick`
* execute: `resume export resume --format pdf --theme slick`
