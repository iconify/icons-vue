<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gbfk04btw"/><path class="zx0kssbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:music-alt-3" /></template>
<style>
.gbfk04btw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.297 36.017c1.064 2.177-.524 5.151-3.547 6.644s-6.336.94-7.4-1.237h0c-1.065-2.176.524-5.15 3.547-6.643q0 0 0 0c3.023-1.494 6.336-.94 7.4 1.236");
}

.zx0kssbjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.623 37.417V4.5c2.112 8.053 8.126 10.351 9.957 17.387c1.36 5.223-1.012 8.128-2.999 11.606c6.817-11.242.284-18.77-6.86-19.563");
}

</style>
