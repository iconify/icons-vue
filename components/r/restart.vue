<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rur0mzb4g"/><path class="bzgnl-bsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:restart" /></template>
<style>
.bzgnl-bsx {
  d: path("m9 2.5l3 3l-3 3m3 1.5v4");
}

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

</style>
