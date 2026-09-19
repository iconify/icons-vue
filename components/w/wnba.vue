<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c5cll3w_q"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wnba" /></template>
<style>
.c5cll3w_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.248 20l-3.41 8l-.59-8l-3.41 8l-.59-8m8.987 8l1.41-8l3.89 8l1.41-8m5.413 4c1.105 0 1.842.895 1.648 2s-1.248 2-2.353 2h-3.3l1.41-8h3.3c1.105 0 1.843.895 1.648 2s-1.248 2-2.353 2m0 0h-3.3m11.283 1.35h-3.544M33.452 28l4.061-8l1.239 8");
}

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

</style>
