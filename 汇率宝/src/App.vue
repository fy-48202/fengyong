<template>
  <div id="app">
    <p>
    <img src="C:\fengyong\title.png" alt="汇率宝" height="100" width="200"/>
    </p>
    <input type="text" value="1">
    <select name="货币选择1" id="money1">
    <option value="cny" title="">人民币</option>
    <option value="usd" title="">美元</option>
    <option value="hkd" title="">港币</option></select>
    <select name="货币选择2" id="money2">
     <option value="cny" title="">人民币</option>
    <option value="usd" title="">美元</option>
    <option value="hkd" title="">港币</option></select>
    <label for=""></label>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
