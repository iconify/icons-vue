<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8u760b4u"/><path class="q05ro5xds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reader-engagement" /></template>
<style>
.p8u760b4u {
  d: path("M3.5 3v17.5H21");
}

.q05ro5xds {
  d: path("M6.5 16.5L10 12l2.5 2.5l3-3.5m3-2.5c-2.75-2-3.25-3.5-3.25-4.5c0-1.25 1-2 1.75-2s1.25.5 1.5 1.25C18.75 2.5 19.25 2 20 2s1.75.75 1.75 2c0 1-.5 2.5-3.25 4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
