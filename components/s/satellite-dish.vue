<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nuocqebsv"/><path class="pswg8r1jz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-dish" /></template>
<style>
.nuocqebsv {
  d: path("M4.5 8A8.5 8.5 0 0 0 16 19.5Zm5.75 5.75L15 9m-.25-1a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.pswg8r1jz {
  d: path("m8 18l-2 3.5h6m5.035-17.364a4 4 0 0 1 2.829 2.829");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
