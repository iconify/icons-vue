<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gohvynseu"/><circle class="qm6uf1bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:traintime" /></template>
<style>
.gohvynseu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.077 11.704h27.846v5.056H10.077zm0 9.768h27.846v5.056H10.077zM37.15 7h-26.3m-.773 24.239h27.846v5.056H10.077zM10.85 41h26.3m-22.19 2.51V4.49M33.27 43.4V4.6");
}

.qm6uf1bwv {
  cx: 24.001px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
