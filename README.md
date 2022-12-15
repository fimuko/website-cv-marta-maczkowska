# website-cv-marta-maczkowska
initialized with npm, using gh-pages package to deploy
build files are in `./dist`
this is meant to run on github pages, in the `gh-pages` branch of this repo

## How to make updates to the webpage?
as per this: https://www.youtube.com/watch?v=SKXkC4SqtRk

1. update your (static) files in `/dist`, 
2. push to remote (main), 
3. then run `npm run deploy` which will push the files in `/dist` to `gh-pages` remote branch (which is what github pages will use)  
