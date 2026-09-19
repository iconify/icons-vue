<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rp_015jka"/><rect class="us149l0-i"/><path class="s-p93bbez"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stove" /></template>
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

.rp_015jka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.664 24h1.849m.987 2.843h-2.836v-5.686H38.5m-5.62 0l-1.878 5.686l-1.879-5.686");
}

.s-p93bbez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.041 21.157h3.757m-1.878 5.686v-5.686M9.612 26.22c.348.454.784.623 1.39.623h.84c.782 0 1.415-.635 1.415-1.418v-.007c0-.783-.633-1.418-1.414-1.418h-.927A1.42 1.42 0 0 1 9.5 22.58h0c0-.786.636-1.423 1.42-1.423h.834c.607 0 1.043.17 1.391.623");
}

.us149l0-i {
  width: 3.757px;
  height: 5.686px;
  x: 22.582px;
  y: 21.157px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.879px;
  ry: 1.879px;
}

</style>
