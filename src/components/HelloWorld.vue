<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      I am a politeknik student, I took a web developemnt course. My hobby is online shopping.
    </p>
    <h3>Student ID</h3>
    <br>
    19FTT1196
    
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