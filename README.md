npm init -y

npm i typescript -D

npx tsc --init

npm i ts-node nodemon -D

"scripts": {
  "dev": "nodemon --watch 'src/' --exec 'ts-node src/app.ts' -e ts",
},
