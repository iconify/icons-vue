<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w1fk33_5u"/><path class="l3hruybqr"/><circle class="y9h021bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:musicplayergo" /></template>
<style>
.l3hruybqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.87 5.75a19.43 19.43 0 1 0 21.56 19.32");
}

.w1fk33_5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.76 17.75v14.66a1 1 0 0 0 1.06 1a1.06 1.06 0 0 0 .57-.17L31.2 26a1 1 0 0 0 .29-1.44a1.3 1.3 0 0 0-.29-.29l-10.8-7.39a1 1 0 0 0-1.64.87");
}

.y9h021bay {
  cx: 24px;
  cy: 5.63px;
  r: 2.13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
