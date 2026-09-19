<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pkomkr00s"/><path class="echkk_bxf"/><path class="dwp20bbta"/><circle class="co5fnsbxc"/><path class="ttwlwdhfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nextclod-passwords" /></template>
<style>
.co5fnsbxc {
  cx: 13.5px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dwp20bbta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.257 25.491a2.5 2.5 0 1 1-.006-2.99");
}

.echkk_bxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.5 39.5H27c1.662 0 3-1.338 3-3v-25c0-1.662-1.338-3-3-3h-1.5");
}

.pkomkr00s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.25 33H4.5V15h21.75M30 15h13.5v18H30");
}

.ttwlwdhfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 8.5H33c-1.662 0-3 1.338-3 3v25c0 1.662 1.338 3 3 3h1.5");
}

</style>
