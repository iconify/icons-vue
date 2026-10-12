<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zq5r1db3x"/><circle class="xe95m5bil"/><circle class="uit8fi3go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:music-circle-sharp" /></template>
<style>
.uit8fi3go {
  cx: 17.75px;
  cy: 15.25px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe95m5bil {
  cx: 6.25px;
  cy: 17.25px;
  r: 2.75px;
}

.zq5r1db3x {
  d: path("M9 17.25V5.533l.8-.163l9.5-1.9l1.2-.245V15.25");
}

</style>
