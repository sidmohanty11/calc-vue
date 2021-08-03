<template>
  <Calculator />
</template>

<script>
import Calculator from './components/Calculator.vue';

export default {
  components: { Calculator },
  name: "App",
};
</script>

<style>
  #app {
    background: #b92b27;  
    background: -webkit-linear-gradient(to right, #1565C0, #b92b27);
    background: linear-gradient(to right, #1565C0, #b92b27);
    font-family: 'Georama', sans-serif;
    font-weight: 300;
    display: flex;
    justify-content: center;
    align-items: center;
    position:fixed;
    padding:0;
    margin:0;
    top:0;
    left:0;
    width: 100%;
    height: 100%;
  }
</style>