# install typescript locally not globally

npm i typescript --save-dev

# initialize 
npx tsc --init

# compiling the project (in bash)
npx tsc 


# run the project
node  *.js 


# ts-node
npm install -D ts-node
npm install -D tslib @types/node

npx ts-node reptile.ts

# debug typescript in vs code
select src/index.ts

run debugger