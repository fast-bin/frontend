<template>
  <div>
    <ViewPaste/>
  </div>
</template>

<script>
// import CreatePaste from './components/CreatePaste.vue'
import ViewPaste from "./components/CreatePaste.vue"

export default {
  name: 'App',
  components: {
    // CreatePaste,
    ViewPaste
  }
}
</script>

<style>
:root {
  --background-color: #0d0d0d;
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
