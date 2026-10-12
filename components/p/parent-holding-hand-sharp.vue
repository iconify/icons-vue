<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="b6f2r6r8q"/><path class="cc8ylbbhq"/><circle class="h-auvl8jn"/><path class="w3t3hktlf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parent-holding-hand-sharp" /></template>
<style>
.b6f2r6r8q {
  cx: 7px;
  cy: 4.5px;
  r: 1.75px;
}

.cc8ylbbhq {
  d: path("M4.5 8.75h5v6.5h-5zm1.25 6.5v6m2.5-6v6");
}

.h-auvl8jn {
  cx: 16.75px;
  cy: 10px;
  r: 1.75px;
}

.w3t3hktlf {
  d: path("M14.75 12.75h4v5h-4zm.75 4.75v3.75M18 17.5v3.75M9.5 10.5h3l1.5 2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
