<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="okeowbp_m"/><path class="if6ty8b3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monk-robe-sharp" /></template>
<style>
.if6ty8b3j {
  d: path("m10 4.5l2 3l2-3m1.92 2.51l1.16.73l.42.26l-.32.38l-7.86 9.49l-.32.38l-.46-.2l-1.33-.6l-.46-.2l.32-.38l8.11-9.74l.32-.38z");
}

.okeowbp_m {
  d: path("M10.25 2.75h4.25l.66.35l3.43 1.8l.66.35l.19.72l1.62 6.06l.19.72l-.74.12l-1.52.26l-.74.12l-.21-.72l-.08-.31l-.016-.054l-.11.02l.016.054l1.05 8.27l.1.74H5l.1-.74l1.05-8.27l.007-.055l-.11-.02l-.007.055l-.08.31l-.21.72l-.74-.12l-1.52-.26l-.74-.12l.19-.72l1.62-6.06l.19-.72l.66-.35l3.43-1.8l.66-.35z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
