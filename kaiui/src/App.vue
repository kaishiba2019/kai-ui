<template>
  <div id="app">
    <h1>开始吧组件库</h1>
    <div>
      按钮
    </div>
    <!-- <btn></btn> -->
    <kai-btn></kai-btn>
  </div>
</template>

<script>
import btn from './components/button/btn.vue'
export default {
  name: 'app',
  components: {
    btn
  }
}
</script>

<style lang="less">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

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
