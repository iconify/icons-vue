<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ahdm3ko7o"/><path class="nqwzuwbrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pegboard-display" /></template>
<style>
.ahdm3ko7o {
  d: path("M2.5 2.5h19V6h-19ZM12 6v5.25M5 9h14v12.5H5Z");
}

.nqwzuwbrj {
  d: path("M10.5 10.75h3v1h-3ZM8 14h8v5H8ZM5.5 4.25h.01m12.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
