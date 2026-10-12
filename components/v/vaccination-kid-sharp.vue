<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="kwdm2lb4x"/><path class="v4vgeob4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vaccination-kid-sharp" /></template>
<style>
.kwdm2lb4x {
  cx: 8.25px;
  cy: 8.5px;
  r: 2.5px;
}

.v4vgeob4u {
  d: path("M3.25 21.25V18a5 5 0 0 1 5-5a5 5 0 0 1 5 5v3.25ZM16.5 6.5h4V16h-4zm0 3h2m-2 3h2m0 3.5v4.75m0-14.25V3.25m-1.5 0h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
