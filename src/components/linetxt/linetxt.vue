<template>
  <div class="des-title">
    <div class="line"></div>
    <div class="text">{{txt}}</div>
    <div class="line"></div>
  </div>
</template>

<script type="text/ecmascript-6">
  export default {
    props: {
      txt: {
        type: String
      }
    }
  };
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .des-title
    display: flex
    width: 80%
    margin: 28px auto 24px auto
    .line
      flex: 1
      position: relative
      top: -6px
      border-bottom: 1px solid rgba(255, 255, 255, .2)
    .text
      padding: 0 12px
      font-weight: 700
      font-size: 14px
</style>
