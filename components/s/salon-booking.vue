<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hemn-9eke"/><path class="d4o3t2fhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:salon-booking" /></template>
<style>
.d4o3t2fhx {
  d: path("M6.5 12.5h3v3h-3ZM17 18.75l4-5.25M14.25 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M19 18.75l-4-5.25m3.75 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hemn-9eke {
  d: path("M11.4 20H2.5V4.5h16v7.7M7 2.5v4m7-4v4m-11.5 3h16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
