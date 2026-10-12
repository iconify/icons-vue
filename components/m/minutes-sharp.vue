<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="klcrqdbde"/><circle class="upu83lbfh"/><path class="lj9r6l14u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:minutes-sharp" /></template>
<style>
.klcrqdbde {
  d: path("M9.75 21.25h-5.5V2.75h13v7M7.5 7H14m-6.5 3.5H14M7.5 14h3");
}

.lj9r6l14u {
  d: path("M17 15v2l1.25.75");
}

.upu83lbfh {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
