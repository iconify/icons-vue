<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="alclthb-l"/><path class="ryb47vbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newspaper-rolled" /></template>
<style>
.alclthb-l {
  d: path("M3.5 12a2.5 6 0 1 0 5 0a2.5 6 0 1 0-5 0Z");
}

.ryb47vbyp {
  d: path("M6 6h11.5a2.5 6 0 0 1 0 12H6m6.5-12v12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
