<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="y4szrx68z"/><circle class="ot-ydxb8o"/><path class="i_uxusbwl"/><circle class="d-8clwncb"/><circle class="cbq7e-b9e"/><path class="e40u1lb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:teddy-bear-toy-sharp" /></template>
<style>
.cbq7e-b9e {
  cx: 18.75px;
  cy: 15px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.d-8clwncb {
  cx: 5.25px;
  cy: 15px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.e40u1lb6y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.9 6.75h.01m2.19 0h.01");
}

.i_uxusbwl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 12.25H16v9h-2.5v-3h-3v3H8v-9z");
}

.ot-ydxb8o {
  cx: 12px;
  cy: 7px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y4szrx68z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.33 6.33a1.75 1.75 0 1 1 2-2l-1.6.4zm3.34-2a1.75 1.75 0 1 1 2 2l-.4-1.6z");
}

</style>
