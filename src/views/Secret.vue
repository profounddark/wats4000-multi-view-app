<template>
  <div class="component">
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        message: 'There are no secrets here.'
      }
    }
  }
</script>

<style scoped>
  .component {
    background:white;
    
  }
  h1 {
      text-align:center;
      font-size: 3rem;
  }

</style>