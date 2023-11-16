<template>
  <h1>Hello header</h1>
  <p>This is a header with Vue.Js</p>
</template>

<script>

export default {
  name: 'TheHeader',
  props: {
    msg: String
  }
}

</script>

<style>

h1 {
  color: #42b983;
}

</style>