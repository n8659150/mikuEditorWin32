<template>
  <div id="app">
    <mainArea/> 
  </div>
</template>

<script>
import mainArea from "./components/mainArea";
export default {
  name: "App",
  components: {
    mainArea
  }
};
</script>

<style>
#app {
  min-height: 100%;
  flex: 1;
  display: flex;
  flex-direction: column;
}
</style>
