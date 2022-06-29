
<script lang="ts">
  import Router from 'svelte-spa-router';
  import Homepage from './pages/Homepage.svelte';
  let routes = {
    "/": Homepage,
  };
</script>

<main>
  <Router {routes} /> 
</main>

<style>
</style>