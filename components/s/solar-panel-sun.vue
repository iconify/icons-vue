<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdy4bcbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-panel-sun" /></template>
<style>
.cdy4bcbfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12.5h15L18.5 21h-15Zm-1.25 4.25h15M13.5 12.5L11 21M9.75 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM12 3.75V2M8.25 7.5H6.5m9.25 0h1.75M9.25 4.75L8 3.5m6.75 1.25L16 3.5");
}

</style>
