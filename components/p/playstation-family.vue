<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="eswhijr5e"/><path class="siav_ybvw"/><circle class="me_wxoons"/><path class="hrwr84moj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:playstation-family" /></template>
<style>
.eswhijr5e {
  width: 15.5px;
  height: 15.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.hrwr84moj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.232 30.613l3.483 3.482l-3.483 3.483a2.5 2.5 0 0 0 3.536 3.535l3.482-3.482l3.482 3.482a2.5 2.5 0 0 0 3.536-3.535l-3.483-3.483l3.483-3.482a2.5 2.5 0 0 0-3.536-3.535L13.25 30.56l-3.482-3.482a2.5 2.5 0 0 0-3.536 3.535");
}

.me_wxoons {
  cx: 34.093px;
  cy: 34.093px;
  r: 8.407px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.siav_ybvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.451 6.465l-6.532 11.742C25.223 19.46 26.13 21 27.561 21h13.065c1.433-.002 2.337-1.541 1.64-2.793l-6.53-11.742a1.88 1.88 0 0 0-3.284 0");
}

</style>
