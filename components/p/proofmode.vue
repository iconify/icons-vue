<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wepxf4b6w"/><circle class="ixa2ttbsg"/><path class="bge1v3hse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proofmode" /></template>
<style>
.bge1v3hse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 15.5v28.254");
}

.ixa2ttbsg {
  cx: 24px;
  cy: 24px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wepxf4b6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 43.754A21.511 21.511 0 1 1 24 45.5");
}

</style>
