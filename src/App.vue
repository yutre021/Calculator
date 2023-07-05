<template>
  <div id="app">
    <b-container>
  <h1>Calculadora</h1>
  <Calculator/>
  </b-container>
  </div>
</template>

<script>
import Calculator from './main/Calculator.vue'




export default {
  components: { Calculator }
}
</script>

<style>

@font-face {
  font-family: "RobotoMono";
  src: url("./fonts/RobotoMono-Thin.ttf");
}

* {
  font-family: "RobotoMono", monospace;
}

body {
  margin:0;
}
#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  text-align: center;
  align-items: center;
  color: #fff;
  background: linear-gradient(to right, rgb(83, 105,118), rgb(41, 46, 73))
}
</style>
