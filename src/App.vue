<template>
  <h1>{{ title }}</h1>
</template>

<script>
import Model from "./components/Modal.vue";

export default {
  name: 'App',
  components: {Model},
  data(){
    return {
      title:'My first Vue App ;)'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
