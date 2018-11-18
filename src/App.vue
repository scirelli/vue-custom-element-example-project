<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="./assets/logo.png"
    >
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <vue-web-component msg="Hi Steve!" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import VueWebComponent from './components/VueWebComponent.vue';

export default {
    name:       'App',
    components: {
        HelloWorld,
        VueWebComponent
    }
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
