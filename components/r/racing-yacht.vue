<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0p7fcb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:racing-yacht" /></template>
<style>
.g0p7fcb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3v11.75H4Zm2.75 2l6.25 9.75h-6.25ZM3 17.75h18C19.5 20 17.5 21 14.5 21H6c-1.5 0-2.5-1.25-3-3.25Z");
}

</style>
