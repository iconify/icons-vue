<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aoyg3l1rx"/><path class="ixxf3kb_l"/><rect class="ows1z1zgv"/><path class="uxkaofdkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:transmission-remote" /></template>
<style>
.aoyg3l1rx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.36 19.76a6.52 6.52 0 0 1 3.7 5.89c0 2.59-1.51 4.84-3.7 5.89m4.015 7.445c4.828-2.498 8.125-7.529 8.125-13.336S39.203 14.8 34.375 12.302M19.09 17.966h5.558a3 3 0 0 1 3 3v16.148a3 3 0 0 1-3 3H8.5a3 3 0 0 1-3-3V20.966a3 3 0 0 1 3-3h5.57");
}

.ixxf3kb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.069 14.37h5.017v12.815h-5.017z");
}

.ows1z1zgv {
  width: 19.169px;
  height: 6.484px;
  x: 6.994px;
  y: 7.886px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.242px;
  ry: 3.242px;
}

.uxkaofdkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.086 32.579v-5.394h-5.017v5.394h-1.96l4.496 4.615l4.497-4.615z");
}

</style>
