<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="nvghvqbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-dock" /></template>
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

.nvghvqbmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.306 27.92c.924 1.202 2.083 1.65 3.695 1.65h2.232a3.76 3.76 0 0 0 3.76-3.76v-.015a3.76 3.76 0 0 0-3.76-3.76H22.77a3.764 3.764 0 0 1-3.763-3.763A3.77 3.77 0 0 1 22.78 14.5h2.219c1.612 0 2.77.448 3.695 1.651M20.5 33.5h7");
}

</style>
