<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ukf7cv5sc"/><circle class="zz_h0qbmm"/><path class="blfun_b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nothing-camera" /></template>
<style>
.blfun_b6f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 33V15a3.46 3.46 0 0 0-3.42-3.5H8a3.46 3.46 0 0 0-3.5 3.42V33a3.46 3.46 0 0 0 3.42 3.5H40a3.46 3.46 0 0 0 3.5-3.42z");
}

.ukf7cv5sc {
  cx: 24px;
  cy: 24px;
  r: 6.85px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zz_h0qbmm {
  cx: 38.88px;
  cy: 16.06px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
