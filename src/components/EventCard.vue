<template>
  <h1 v-if @click="handler(arg, event)"></h1>
</template>

<script>
export default {
  data() {
    return {
      quote: 'i want to be single'
    }
  }
}
</script>

<style>
</style>
