<template>
  <div id="app">
    <h1>VueJs Calculator</h1>
    <Calculator/>
    <span>Author: Icaro Vieira</span>
  </div>
</template>

<script>
import Calculator from "./main/Calculator"

export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Rajdhani&display=swap');

#app {
  font-family: 'Rajdhani', sans-serif;
  /*font-family: Avenir, Helvetica, Arial, sans-serif;*/
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
