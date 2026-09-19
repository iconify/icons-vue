<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j-gf15bqr"/><circle class="egplo3b0p"/><path class="mqdeegc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moscow-transport" /></template>
<style>
.egplo3b0p {
  cx: 24px;
  cy: 20.826px;
  r: 5.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j-gf15bqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.163 31.663a15.326 15.326 0 1 1 21.674 0L24 42.5");
}

.mqdeegc9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.775 28.051a10.217 10.217 0 1 1 14.45 0L20.388 38.888");
}

</style>
