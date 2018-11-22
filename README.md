# vue-web-component
```
Following this tutorial: https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/

There is a Vue component defined under ./src/components, which is VueWebComponent.vue
Then I have run: npm run build:web, which defined as: vue-cli-service build --target wc --name my-custom-element ./src/build_web_component.js
It generate the a dist folder with my-custom-element.js. 
I copied the js file to public folder. 

Then include the my-custom-element.js in index.html. 
Consume the <my-custom-element> custom tag in App.vue

Run: npm run serve, visit: localhost:8080. 
```


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
