<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="t2zlgc8_u"/><circle class="be4hwp76b"/><circle class="i2o5n6bvz"/><path class="p5vidpare"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:words-of-wonders-crossword" /></template>
<style>
.be4hwp76b {
  cx: 12.375px;
  cy: 17.945px;
  r: 7.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i2o5n6bvz {
  cx: 35.625px;
  cy: 17.945px;
  r: 7.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p5vidpare {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.669 14.191l-2.13 8.521l-2.13-8.521l-2.13 8.521l-2.13-8.521m15.798 22.124c-1.598 0-2.77-1.278-2.77-2.769V30.67c0-1.597 1.279-2.875 2.77-2.875h0a2.864 2.864 0 0 1 2.876 2.875v2.77a2.864 2.864 0 0 1-2.876 2.875m15.972-22.124l-2.13 8.521l-2.13-8.521l-2.13 8.521l-2.13-8.521M18.933 26.035l-1.853-1.79m13.846 0l-1.854 1.79");
}

.t2zlgc8_u {
  cx: 24px;
  cy: 32.055px;
  r: 7.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
