<template>
  <div id="app">
    <h1>Calculadora JM</h1>
    <CalculatorComponent />
  </div>
</template>

<script>
/* eslint eqeqeq: "off", curly: "error" */

import CalculatorComponent  from "./main/CalculatorComponent"

export default {
  components: { CalculatorComponent }
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
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
  background: linear-gradient(to right, rgb(85, 105, 118), rgb(41, 46, 73));
}
</style>

