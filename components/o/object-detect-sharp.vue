<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m4b4dzzhx"/><path class="toehbab5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:object-detect-sharp" /></template>
<style>
.m4b4dzzhx {
  d: path("M3.25 7.5V3.25H7.5m9 0h4.25V7.5m0 9v4.25H16.5m-9 0H3.25V16.5m9.44-9.6l3.37 1.95l.69.4v5.5l-.69.4l-3.37 1.95l-.69.4l-.69-.4l-3.37-1.95l-.69-.4v-5.5l.69-.4l3.37-1.95l.69-.4z");
}

.toehbab5l {
  d: path("M7.6 9.45L12 12l4.4-2.55M12 12v5.1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
