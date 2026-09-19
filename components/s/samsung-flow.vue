<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="czah-lrgn"/><circle class="gagr6qbdl"/><circle class="a28t61nws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-flow" /></template>
<style>
.a28t61nws {
  cx: 37.974px;
  cy: 9.044px;
  r: 3.897px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.czah-lrgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.077 24.234H14.114c-5.042 0-9.364 4.045-9.24 9.086a8.864 8.864 0 0 0 8.639 8.638c5.04.124 9.086-4.197 9.086-9.24V15.143a6.1 6.1 0 0 1 6.099-6.099h5.379");
}

.gagr6qbdl {
  cx: 37.974px;
  cy: 24.234px;
  r: 3.897px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
