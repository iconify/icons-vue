<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="xh4evtb-j"/><path class="ftsc01bvr"/><circle class="u5pl82bll"/><path class="kz85adcdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleeping-sharp" /></template>
<style>
.ftsc01bvr {
  d: path("m7 12.75l1.125.952l1.125-.952m2.5 0l1.125.952L14 12.75");
}

.kz85adcdz {
  d: path("M16 2.75h4l-4 4h4");
}

.u5pl82bll {
  cx: 10.5px;
  cy: 17px;
  r: 1px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xh4evtb-j {
  cx: 10.5px;
  cy: 13.5px;
  r: 7.75px;
}

</style>
