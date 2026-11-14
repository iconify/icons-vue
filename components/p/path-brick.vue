<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbekm2b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:path-brick" /></template>
<style>
.pbekm2b0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21.5l6-18h6l6 18Zm2-6h14m-12-6h10m-5 12v-6m-2.5 0v-6m5 6v-6m-2.5 0v-6");
}

</style>
