<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cpaimfkes"/><path class="dhi79kbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-landslide" /></template>
<style>
.cpaimfkes {
  d: path("M2.5 3L15 21h6.5M8 4l2.5-1.5l1.75 2L11 6.75L8.5 6.5Zm5 5l2.5-1.25l1.75 2L16 12l-2.5-.25Z");
}

.dhi79kbon {
  d: path("m17 15l2-1.75l2 1.5l-.5 2.5l-2.75.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
