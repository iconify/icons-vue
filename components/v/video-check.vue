<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zr4fqjbaq"/><path class="a5qcfu_xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-check" /></template>
<style>
.a5qcfu_xs {
  d: path("m6.5 12l1.75 1.75l3.25-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zr4fqjbaq {
  d: path("M2.5 6h13v12h-13Zm13 4.5l6-3.5v10l-6-3.5Z");
}

</style>
