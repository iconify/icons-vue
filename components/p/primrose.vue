<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c9ka_3gce"/><path class="vdo1j_06c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:primrose" /></template>
<style>
.c9ka_3gce {
  d: path("M9.25 8.25a3.5 3.5 0 1 1 5.5 0a3.5 3.5 0 1 1 1.5 5.25a3.5 3.5 0 1 1-4.25 3a3.5 3.5 0 1 1-4.25-3a3.5 3.5 0 1 1 1.5-5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vdo1j_06c {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
