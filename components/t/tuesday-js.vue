<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="no0q_1b_o"/><circle class="typ3uf2mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tuesday-js" /></template>
<style>
.no0q_1b_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.937 5.5H23.62c9.081 0 16.444 7.31 16.444 16.326h0c0 8.62-6.75 15.754-15.414 16.294M15.95 5.5v32.652M24.649 5.5v32.652");
}

.typ3uf2mi {
  cx: 20.299px;
  cy: 38.151px;
  r: 4.349px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
