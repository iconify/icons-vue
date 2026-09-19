<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><path class="x13_4y70r"/><rect class="bpmbpbb6s"/><path class="h1e6a0bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:roku" /></template>
<style>
.bpmbpbb6s {
  width: 4.771px;
  height: 6.321px;
  x: 18.638px;
  y: 21.976px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.385px;
  ry: 2.385px;
}

.h1e6a0bln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.23 21.976v3.936a2.385 2.385 0 0 0 2.385 2.385h0A2.385 2.385 0 0 0 38 25.912v-3.936m0 3.936v2.385m-11.858-9.541v9.541m.001-2.027l4.319-4.297m-2.945 2.93l3.396 3.38");
}

.x13_4y70r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10 28.297v-9.541h3.124c1.765 0 3.197 1.435 3.197 3.204s-1.432 3.205-3.197 3.205H10m3.123 0l3.124 3.13");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
