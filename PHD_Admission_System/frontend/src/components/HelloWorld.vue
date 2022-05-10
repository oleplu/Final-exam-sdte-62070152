<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
  <div class="grid grid-cols-4">
    <div>A</div>
    <div>B</div>
    <p>C</p>
    <p>D</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
