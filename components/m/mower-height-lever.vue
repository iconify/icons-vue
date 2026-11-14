<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siwy27bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mower-height-lever" /></template>
<style>
.siwy27bim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 3v18m-3-14h3m-3 5h3m-3 5h3m-18 2.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.25-1.25L15 9.5");
}

</style>
