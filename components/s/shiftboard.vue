<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yaqj32hvj"/><circle class="tj2bmz04y"/><circle class="xwyhn5m7a"/><path class="lnb1j6b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shiftboard" /></template>
<style>
.lnb1j6b1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.815 36.905a5.151 5.151 0 1 1-9.952-2.666m6.51-23.144l-6.51 23.144M42.324 13.76l-6.51 23.145");
}

.tj2bmz04y {
  cx: 10.651px;
  cy: 12.427px;
  r: 5.151px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xwyhn5m7a {
  cx: 10.651px;
  cy: 35.209px;
  r: 5.151px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yaqj32hvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.373 11.095a5.151 5.151 0 1 1 9.951 2.666");
}

</style>
