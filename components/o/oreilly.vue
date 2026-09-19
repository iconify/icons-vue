<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="nrv9x7qhg"/><circle class="o5wwg_qam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oreilly" /></template>
<style>
.nrv9x7qhg {
  cx: 20.588px;
  cy: 24.977px;
  r: 16.088px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o5wwg_qam {
  cx: 39.169px;
  cy: 11.267px;
  r: 4.331px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
