<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t__vkvfxw"/><path class="aige1qb_m"/><path class="v-fa9mb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:peoplesync" /></template>
<style>
.aige1qb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.52 32.67l-8.915 9.83l16.63-1.65m-23.001 1.09c-7.803.284-16.06-25.212 13.783-32.88");
}

.t__vkvfxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 10.947S53.018 27.61 21.146 41.78");
}

.v-fa9mb2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.633 5.5l11.82 3.167l-8.317 8.317");
}

</style>
