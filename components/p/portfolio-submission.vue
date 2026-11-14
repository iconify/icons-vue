<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i7ji2n6zu"/><path class="hly-ncb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:portfolio-submission" /></template>
<style>
.hly-ncb_j {
  d: path("M5 10V8a1 1 0 0 1 1-1h10.5v11.5h-2m-12 .5l4-3.5l3 2.5m1.25-4.5h.01m8.49-.5V3M17 5.25L19.25 3l2.25 2.25");
}

.i7ji2n6zu {
  d: path("M2.5 10h12v11.5h-12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
