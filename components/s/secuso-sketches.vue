<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wt4wofb9c"/><circle class="yypvstenu"/><path class="xjfep-b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:secuso-sketches" /></template>
<style>
.wt4wofb9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.05 4.5v3.52m-2.7-3.52v3.52M30.648 4.5v3.52M27.947 4.5v3.52M25.246 4.5v3.52M22.545 4.5v3.52M19.843 4.5v3.52M17.142 4.5v3.52M14.44 4.5v3.52M9.65 6.232h28.701V43.5H9.65z");
}

.xjfep-b9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.246 17.202l4.031 1.648l3.35-3.874l3.319 4.344m-16.01 11.474v-2.319l2.75 2.319v-2.319l2.749 2.319v-2.319l2.75 2.319v-2.319l2.749 2.319v-2.319l2.75 2.319v-2.319m-13.543 7.307v-2.494l2.742 2.494v-2.494l2.742 2.494v-2.494l2.742 2.494v-2.494M11.74 4.5v3.52");
}

.yypvstenu {
  cx: 18.786px;
  cy: 17.867px;
  r: 3.523px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
