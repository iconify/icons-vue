<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ihhmrgbtj"/><path class="nfej8rb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smartwatch-health" /></template>
<style>
.ihhmrgbtj {
  d: path("M7.5 6h9a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1h-9a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1ZM9 6l.75-3.5h4.5L15 6M9 18l.75 3.5h4.5L15 18");
}

.nfej8rb1w {
  d: path("M12 13.25S9.3 11.65 9.25 10c.05-.87.68-1.5 1.5-1.5c.5 0 .98.3 1.25.75c.27-.45.75-.75 1.25-.75c.82 0 1.45.63 1.5 1.5c-.05 1.65-2.75 3.25-2.75 3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
