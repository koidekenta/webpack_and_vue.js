<template>
  <div>
    <h1>App.vue</h1>
		<Header></Header>
		<Body></Body>
  </div>
</template>

<script>
import Header from "./Header.vue"
import Body from "./Body.vue"

export default {
  components: {
    Header,
    Body,
  },
}
</script>

<style>

</style>