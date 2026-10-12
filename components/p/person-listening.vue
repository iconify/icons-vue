<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="qexqi5bar"/><path class="vup2qpbxk"/><rect class="nra1s5bxb"/><rect class="n4a9yurdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-listening" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4a9yurdx {
  width: 3px;
  height: 4.5px;
  x: 18px;
  y: 9px;
  rx: 1.25px;
}

.nra1s5bxb {
  width: 3px;
  height: 4.5px;
  x: 3px;
  y: 9px;
  rx: 1.25px;
}

.qexqi5bar {
  cx: 12px;
  cy: 9.5px;
  r: 3px;
}

.vup2qpbxk {
  d: path("M6 21.25h12a.75.75 0 0 0 .75-.75c0-2.6-3.02-4.5-6.75-4.5s-6.75 1.9-6.75 4.5a.75.75 0 0 0 .75.75M4.5 9a7.5 6 0 0 1 15 0");
}

</style>
