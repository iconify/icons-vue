<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ihwnebbjv"/><path class="x77xhwber"/><path class="ldnins8me"/><path class="dtc2k7idd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seahorse-marine-sharp" /></template>
<style>
.dtc2k7idd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 17.25c.75 2 0 4-2 4h-2v-3.5l1.5.5");
}

.ihwnebbjv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.63 11.03l1.84.94l.53.28l-.51.31l-1.88 1.13l-.51.31v-3.25z");
}

.ldnins8me {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 6h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x77xhwber {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 7l.417-3.75h2.583l.75-.5l.75.75l2.279.912l-.779 2.338c-.5 1.5 1.5 2.75 1.5 5.75c0 2.5-1.75 4.25-4 4.75C10 17 8.5 13.5 10 10.75l1.066-1.776zm0 .25l-5.5.5");
}

</style>
