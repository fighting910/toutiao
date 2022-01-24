<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
    <h1>头条</h1>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less"></style>
