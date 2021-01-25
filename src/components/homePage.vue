<template>
  <div id="homePage">
    <div>{{$store.state.test}}</div>
  </div>
</template>

<script>
export default {
  name: 'homePage',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#homePage{
  height: 100vh;
  width: 100%;
}
</style>
