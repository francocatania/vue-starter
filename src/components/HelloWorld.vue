<template>
  <div class="hello">
    <h1>Vue starter template</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import '@/scss/_globals.scss';

  h1 {
    @include media('tablet', 'max') {
      font-size: rem-calc(16);
      color: blue;
    }
  }
</style>
