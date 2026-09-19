<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="t7sq_mbuy"/><path class="qs1c2cbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mufg-mdc" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qs1c2cbbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27 17.35h2.5c5.247 0 9.5 3.246 9.5 7.25s-4.253 7.25-9.5 7.25H21v-3.594m0-3.594V17.35");
}

.t7sq_mbuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 22.2V9.7l8 4.75l8-4.75v12.5m-.218 13.708a9.5 7.25 0 0 1-10.44 2.802a9.5 7.25 0 0 1-6.833-6.644a9.5 7.25 0 0 1 6.048-7.073a9.5 7.25 0 0 1 10.721 2.096");
}

</style>
