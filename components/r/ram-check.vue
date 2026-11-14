<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gmlvv0bjg"/><path class="by8f9v1yj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ram-check" /></template>
<style>
.by8f9v1yj {
  d: path("m9.5 10.5l1.75 1.75L15 8.5");
}

.gmlvv0bjg {
  d: path("M2 6.5h20v9H2Zm3.5 9v3m3-3v3m7-3v3m3-3v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
