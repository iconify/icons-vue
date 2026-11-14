<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csq8ux7-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sla-breach" /></template>
<style>
.csq8ux7-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h11M4 21h11M5.5 3v2.5q0 3.5 4 6.5t4 6.5V21m0-18v2.5q0 3.5-4 6.5t-4 6.5V21M18 14.75v3.5M18 21h.01");
}

</style>
