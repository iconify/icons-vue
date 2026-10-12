<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ox05rfewb"/><path class="mv9nk1boe"/><path class="qjvyleyug"/><path class="knl2yx9sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:microwave-sharp" /></template>
<style>
.knl2yx9sp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 15.75h1.5");
}

.mv9nk1boe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.75h9v8.5h-9z");
}

.ox05rfewb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

.qjvyleyug {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 8.75h.01M18 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
