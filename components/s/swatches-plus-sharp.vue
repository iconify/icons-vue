<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="uc3mcmbxs"/><path class="bd9gzlbmu"/><path class="fxk0gfbtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swatches-plus-sharp" /></template>
<style>
.bd9gzlbmu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17.5h.01");
}

.fxk0gfbtj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.55 6.5l3.15-1.82l1.3-.75l.75 1.3l1.75 3.03l.75 1.3l-1.3.75l-6.4 3.7l-1.3.75V7.25zm-1.3 9.75h12v5h-12Z");
}

.uc3mcmbxs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h6.5v18.5h-6.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
