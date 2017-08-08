<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <router-link to='/child' class='p'>Go to child</router-link>
    <h3>The botui below should reappear after switching to child and back to home</h3>
    <p>The only way right now is to hit refresh</p>
    <p>Is there a way to refresh this in Vue?</p>
    <div class="botui-app-container" id="my-botui-app">
      <bot-ui></bot-ui>
    </div>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
