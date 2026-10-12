<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sutrn8uqz"/><path class="v8rzpubvy"/><circle class="h_aonk51t"/><path class="lryu0zb7p"/><path class="niiog3b_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:password-manager-sharp" /></template>
<style>
.h_aonk51t {
  cx: 16.75px;
  cy: 11.25px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lryu0zb7p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 11.25h.01");
}

.niiog3b_x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 18.75v1.75m12-1.75v1.75");
}

.sutrn8uqz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v15H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v8rzpubvy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11.25h.01m2.99 0h.01m2.99 0h.01");
}

</style>
