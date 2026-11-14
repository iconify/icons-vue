<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd8duab2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sachet" /></template>
<style>
.cd8duab2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.808 16.95L16.95 2.808l.353 1.767l1.768.354l.354 1.768l1.767.353L7.05 21.192l-.353-1.767l-1.768-.354l-.354-1.768Zm2.651-2.652l4.243 4.243m4.596-13.082l4.243 4.243");
}

</style>
