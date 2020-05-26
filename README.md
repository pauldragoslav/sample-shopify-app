## Requirements
```
node -v
```

## Create a project
```
mkdir sample-embedded-app
cd sample-embedded-app
npm init -y
```

## Install React, ReactDOM, and Next.js
```
npm install --save react react-dom next
```

## Create a view
```
mkdir pages
touch pages/index.js
```

## Run your project
```
npm run dev
```
http://localhost:3000/

## Expose your dev environment
```
npm install ngrok -g
ngrok http 3000
```

Source and reference:
https://shopify.dev/tutorials/build-a-shopify-app-with-node-and-react