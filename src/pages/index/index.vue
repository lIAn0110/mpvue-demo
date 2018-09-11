<template>
  <div class="container">
    <i-button type="success">iView-weapp中的按钮组件</i-button>
  </div>
</template>

<script>

export default {
  data() {
    return {}
  },
  methods: {
    goTo(url) {
      this.$router.push(url);
    }
  }
}
</script>

<style scoped>

</style>
