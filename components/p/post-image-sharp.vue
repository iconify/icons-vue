<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><circle class="f73ungbos"/><path class="asf_7zb_n"/><path class="eu42wt9jy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:post-image-sharp" /></template>
<style>
.asf_7zb_n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7H17M2.75 10.5h18.5m-15 7.25L9.75 14l2.75 2.75L14.25 15l3.25 2.75");
}

.eu42wt9jy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 13.5h.01");
}

.f73ungbos {
  cx: 7px;
  cy: 7px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ywno-sh7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
