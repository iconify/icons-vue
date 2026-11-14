<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h4s22dbpt"/><path class="l6ccd3bgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:screw-head-torx" /></template>
<style>
.h4s22dbpt {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0Z");
}

.l6ccd3bgy {
  d: path("m12 6.5l1.625 2.685l3.138.065L15.25 12l1.513 2.75l-3.138.065L12 17.5l-1.625-2.685l-3.138-.065L8.75 12L7.237 9.25l3.138-.065Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
