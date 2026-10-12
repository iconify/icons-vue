<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t_6u2pibf"/><circle class="neks5ib7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ping-pong-sharp" /></template>
<style>
.neks5ib7s {
  cx: 18.25px;
  cy: 19px;
  r: 1.75px;
}

.t_6u2pibf {
  d: path("M10.25 16.02a6.75 6.75 0 1 1 3.5 0v5.23h-3.5v-1.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
