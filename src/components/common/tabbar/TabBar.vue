<template>
  <div class="tab-bar">
     <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'TabBar'
  }
</script>

<style scoped>
  .tab-bar {
    height: 49px;
    background-color: #f6f6f6;
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    display: flex;
    box-shadow: 0 2px 2px 2px rgba(100, 100, 100, .2);
  }
 
</style>
