<template>
  <div class="m-geo">
    <i class="el-icon-location" /> {{ $store.state.geo.position.city }}
    <nuxt-link class="changeCity" to="/changeCity">切换城市</nuxt-link>
    [烟台 天津 德州]
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">

</style>
