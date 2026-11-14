<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv9globig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transform-handles" /></template>
<style>
.iv9globig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h3.5v3.5h-3.5Zm14 0h3.5v3.5h-3.5Zm0 14h3.5v3.5h-3.5Zm-14 0h3.5v3.5h-3.5Zm7-14h3.5v3.5h-3.5Zm0 14h3.5v3.5h-3.5Zm-7-7h3.5v3.5h-3.5Zm14 0h3.5v3.5h-3.5ZM6.75 5h3.5m3.5 0h3.5M6.75 19h3.5m3.5 0h3.5M5 6.75v3.5m0 3.5v3.5m14-10.5v3.5m0 3.5v3.5");
}

</style>
