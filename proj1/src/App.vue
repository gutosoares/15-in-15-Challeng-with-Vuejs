<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>
      <hello>Hello World!</hello>
    </h1>
    <p>more about Vue.js <a href="https://github.com/gutosoares" target="_blank">here</a></p>
  </div>
</template>

<script>
import Hello from './Hello.vue'

export default {
  name: 'app',
  components: {
    'hello': Hello
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

  h1, h2 {
    font-weight: normal;
  }
}

</style>
