<template>
  <div id="app">
      <h1>Monty Hall Problem</h1>
      <Gift />
  </div>
</template>

<script>
import Gift from './components/Gift'

export default {
    name: 'App',
    components: { Gift }
}
</script>

<style>
*{
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
}

body {
    color: #fff;
    background: #fc4a1a;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to right, #f7b733, #fc4a1a);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to right, #f7b733, #fc4a1a); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

}

#app {
    display: flex;
    flex-direction: column;
    align-items: center;
}

#app h1 {
    border: 1px solid #000;
    border-radius: 10px;
    background-color: #0004;
    padding: 20px;
    margin-bottom: 60px;
}
</style>