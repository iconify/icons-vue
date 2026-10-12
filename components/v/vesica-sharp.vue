<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wayxywj4x"/><path class="yrp0w3i5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vesica-sharp" /></template>
<style>
.wayxywj4x {
  d: path("M9 6a6 6 0 1 1 0 12A6 6 0 1 1 9 6m6 0a6 6 0 1 1 0 12a6 6 0 1 1 0-12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrp0w3i5a {
  d: path("M12 6.8a6 6 0 0 1 0 10.4a6 6 0 0 1 0-10.4Z");
}

</style>
