<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="oel5_sb-e"/><path class="xyv9ewbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:petal-maps" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.oel5_sb-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.956a9.43 9.43 0 0 0-9.43 9.43c0 7.383 7.204 16.287 9.084 18.462a.576.576 0 0 0 .872 0c1.837-2.16 8.904-11.079 8.904-18.463A9.43 9.43 0 0 0 24 9.955m0 12.967a3.53 3.53 0 1 1 3.523-3.538v.008A3.523 3.523 0 0 1 24 22.915z");
}

.xyv9ewbef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.197 28.391c-4.146 1.626-7.469 3.088-11.697 1.646m14.741 3.381C16.095 35.044 9.728 37.342 5.5 35.9m25.856-8.544c4.082-.272 7.462.747 11.119 2.15M28.25 32.854c6.5-.961 10.779 1.482 14.25 3.145m-9.693-19.984c3.662-1.16 6.01-.85 9.668.554");
}

</style>
