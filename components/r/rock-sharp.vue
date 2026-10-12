<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mowelwb3x"/><path class="dp67lo3zq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rock-sharp" /></template>
<style>
.dp67lo3zq {
  d: path("m9.5 6.75l2 5.25l-3.25 3.25M11.5 12l5.5-1.5");
}

.mowelwb3x {
  d: path("m3.14 18.04l1.22-5.33l.39-1.71l1.24-1.24l2.27-2.27L9.5 6.25l1.74.21l2.77.33l1.74.21l1.2 1.27l2.1 2.21l1.2 1.27l.22 1.74l.56 4.52l.22 1.74H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
