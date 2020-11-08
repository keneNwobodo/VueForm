<template>
  <div id="app">
    <login />
  </div>
</template>

<script>
import login from "./components/login/login.vue"

export default {
  name: 'App',
  components: {
   login
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
}

#app {
  font-family: Tahoma;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #222;
  background: #092525;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
