<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8pivjban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:police-car-front" /></template>
<style>
.u8pivjban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 12l1.25-4c.25-.9 1-1.5 2-1.5h6.5c1 0 1.75.6 2 1.5l1.25 4M6.25 12h11.5A3.25 3.25 0 0 1 21 15.25a3.25 3.25 0 0 1-3.25 3.25H6.25A3.25 3.25 0 0 1 3 15.25A3.25 3.25 0 0 1 6.25 12M6 18.5V21m12-2.5V21M6.75 15.25h.01m10.49 0h.01M10.875 2h2.25a.875.875 0 0 1 .875.875a.875.875 0 0 1-.875.875h-2.25A.875.875 0 0 1 10 2.875A.875.875 0 0 1 10.875 2M10.5 15.5h3");
}

</style>
