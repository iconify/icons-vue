<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="fil2f8b-s"/><path class="tsdqsjo2p"/><circle class="fvq01fdmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:robot-vacuum-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fil2f8b-s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 8.5h17.5");
}

.fvq01fdmb {
  cx: 12px;
  cy: 14.25px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tsdqsjo2p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
