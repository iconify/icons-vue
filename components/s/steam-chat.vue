<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="n6ktsm30t"/><circle class="z84mwy4js"/><path class="t80zedb9j"/><path class="hwh5bgfpg"/><path class="brpl_vacq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:steam-chat" /></template>
<style>
.brpl_vacq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 0 0 2.5 24a23.14 23.14 0 0 0 2.665 10.297L2.5 45.5l11.174-2.658A21.494 21.494 0 1 0 24 2.5");
}

.hwh5bgfpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("m23.1 18.367l-5.708 8.094m5.62 5.62l8.046-5.757");
}

.n6ktsm30t {
  cx: 31.058px;
  cy: 18.366px;
  r: 7.957px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t80zedb9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.852 33.025l-8.668-3.874M2.56 22.39l11.523 5.15");
}

.z84mwy4js {
  cx: 17.392px;
  cy: 32.081px;
  r: 5.62px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
