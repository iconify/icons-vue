<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="wnxsbdc8l"/><circle class="pvp5qbcdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trt-dinle" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pvp5qbcdk {
  cx: 17.795px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.wnxsbdc8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.623 26.6v8h4m-13.828-8v8m2.269 0v-8l5.3 8v-8m8.286 4h2.6m1.4 4h-4v-8h4m-27.3 8v-8h1.8c1.9 0 3.5 1.6 3.5 3.5v1c0 1.9-1.6 3.5-3.5 3.5zm11.373-13.2v-8h2.6c1.5 0 2.7 1.2 2.7 2.7s-1.2 2.7-2.7 2.7h-2.6m2.698-.002l2.502 2.502M14.49 13.4h5.2m-2.6 8v-8m11.22 0h5.2m-2.6 8v-8");
}

</style>
