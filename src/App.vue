<script>
// 1° importazione
  import appTitle from './components/appTitle.vue'

// 2° registrare componente
  export default{
    components: {
      appTitle
    }
}
</script>

<!-- 3° utilizzare la componente -->
<template>
  <h1><appTitle></appTitle></h1>
</template>

<style>
</style>
