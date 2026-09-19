<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="m54-_3yjg"/><circle class="ow08pwbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sectograph" /></template>
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

.m54-_3yjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.431 25.549c1.728-1.728 6.345-13.409 6.345-13.409s-9.629 4.986-12.198 7.556c-2.255 2.255-2.017 4.71-.61 6.116c1.853 1.853 4.24 1.96 6.463-.263M2.529 23.774l14.73.05c0 4.531 2.199 7.083 6.886 7.083l.16 14.59");
}

.ow08pwbqt {
  cx: 24.823px;
  cy: 23.147px;
  r: 0.75px;
  fill: currentColor;
}

</style>
