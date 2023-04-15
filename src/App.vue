<template>
  <div flex="iii">
    <img
      class="dddd"
      id="ddddd" click="dddd()"
      alt="Vue logo"
      src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue"

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  methods (){
    oddd() {
      let a = "ddd"
      let b = [1,2.3,2,3]
      
      console.log('dd')
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
