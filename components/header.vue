<!-- Please remove this file from your project -->
<template>
  <header class="header">
    <div>
      <h3 class="title  float-md-start mb-0"><a href="/">Toward Better</a></h3>
      <nav class="menu nav nav-masthead justify-content-center float-md-end">
        <!--<a class="nav-link" href="/about" :active="$route.path == 'about'">About</a>-->
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>
<style>
  .title a {
    text-decoration: none;
    color: white;
  }
</style>
