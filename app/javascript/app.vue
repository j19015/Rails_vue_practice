<template>
  <div id="app">
    <p>{{ message }}</p>
    <p>{{message1 }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!",
      message1: "Hello vue!2"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
