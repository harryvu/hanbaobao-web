<template>
  <main>
    <router-view name="nav" />
    <router-view/>
  </main>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
body {
  background-color: #ffd740; 
}
</style>