<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rur0mzb4g"/><path class="x66l1xl9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rotate-cw" /></template>
<style>
.rur0mzb4g {
  d: path("M18.495 9.25A7.5 7.5 0 1 1 12 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x66l1xl9e {
  d: path("m9 2.5l3 3l-3 3");
}

</style>
