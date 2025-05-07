<template>
  <div id="app">
  
    <productoList />
  </div>
</template>

<script>

import productoList from './components/productoList.vue';

export default {
  name: 'App',
  components: {
   
    productoList
  }
};


</script>



<style>

body {
  margin: 0;
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
