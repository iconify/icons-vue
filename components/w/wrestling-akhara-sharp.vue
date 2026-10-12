<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="vx_xyyw4c"/><circle class="nrw5thixb"/><path class="yskvo2bnb"/><path class="hdeen9b5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wrestling-akhara-sharp" /></template>
<style>
.hdeen9b5c {
  d: path("m7 10l5 2.25L17 10M2.75 21h18.5");
}

.nrw5thixb {
  cx: 17px;
  cy: 5px;
  r: 2px;
}

.vx_xyyw4c {
  cx: 7px;
  cy: 5px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yskvo2bnb {
  d: path("M7 7.75V14l-2.25 4.75M7 14l2.25 4.75m7.75-11V14l-2.25 4.75M17 14l2.25 4.75");
}

</style>
