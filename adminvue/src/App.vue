<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <keep-alive>
      <router-view />
    </keep-alive>
  </div>
</template>

<style>
body {
  margin: 0px;
}
</style>
