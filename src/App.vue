<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="less">
  * {
    margin: 0;
    padding: 0;
  }
  html, body {
    width:100%;
    height: 100%;
  }
  .app-container {
    width: 100%;
    height: 100%;
    border: 0px solid red;
  }
</style>
<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  width: 100%;
  height: 100%;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
