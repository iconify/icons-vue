<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fixud3bop"/><path class="c5tdibbhh"/><path class="s6p3z6bxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:text-select" /></template>
<style>
.c5tdibbhh {
  fill: currentColor;
  d: path("M3 9.5h13v5H3Z");
}

.fixud3bop {
  d: path("M3 5h18M3 19h12");
}

.s6p3z6bxv {
  d: path("M19 8.5v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
