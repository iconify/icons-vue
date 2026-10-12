<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cv98drj4r"/><path class="roxelobjv"/><path class="nz12qubkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:xss-script-sharp" /></template>
<style>
.cv98drj4r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75zm0 4h18.5");
}

.nz12qubkf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 11L6 13.5L8.5 16m7-5l2.5 2.5l-2.5 2.5M13 10.5l-2 6");
}

.roxelobjv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
