<template>
  <div class="m-header">
    <div class="icon"></div>
    <h1 class="text">Chicken Music</h1>
  </div>

</template>

<script>
  export default {}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "~common/stylus/variable"
  @import "~common/stylus/mixin"
  .m-header
    position relative
    height 44px
    display flex
    align-items center
    justify-content center
    color: $color-theme
    .icon
      bg-image('logo')
      height 32px
      width 30px
      display inline-block
      background-size 30px 32px
      margin-right 9px
    .text
      font-size $font-size-large
</style>