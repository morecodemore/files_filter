# files_filter
>files_filter - node.js program to truncate files alphabetically

#### The project launch command:
    git clone https://github.com/morecodemore/files_filter.git

install dependencies
   
    npm i

go to the folder with the code

    cd programs

run eslint

    ../node_modules/.bin/eslint sync.js
    ../node_modules/.bin/eslint async.js

start the filtering synchronously

    node sync.js /*from folder name (string)*/  /*to folder name (string)*/  /*delete first folder (boolean)*/

start the filtering asynchronously

    node async.js /*from folder name (string)*/  /*to folder name (string)*/  /*delete first folder (boolean)*/
