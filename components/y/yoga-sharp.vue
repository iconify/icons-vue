<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="xe53owbmy"/><path class="htae59dlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yoga-sharp" /></template>
<style>
.htae59dlp {
  d: path("M4.25 11.5L8.5 13L12 9.5l3.5 3.5l4.25-1.5M12 9.5v6m-7.75 3.75c0-1.75 3.5-3 7.75-3s7.75 1.25 7.75 3v1.5H4.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe53owbmy {
  cx: 12px;
  cy: 5px;
  r: 2px;
}

</style>
