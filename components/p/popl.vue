<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="f_-sa5b4q"/><circle class="ojz50gbrf"/><path class="q54wdgbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:popl" /></template>
<style>
.f_-sa5b4q {
  cx: 13px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

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

.ojz50gbrf {
  cx: 33px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q54wdgbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 16v12M9 24v8m20-8v8m-6-5.333V28m1.71-1.962l.86 1.026m-5.141 0l.86-1.026m4.332-1.576l1.318.232m-7.878.001l1.318-.232m4.93-1.796L26.464 22m-6.928 0l1.16.67m3.216-1.175l.456-1.253m-2.736-.001l.456 1.254");
}

</style>
