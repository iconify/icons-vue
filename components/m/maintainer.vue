<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd6_albjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:maintainer" /></template>
<style>
.rd6_albjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.572 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.437 0 2.76.257 3.882.724M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm13 7.25a2.5 2.5 0 1 0 2.25 2.25m-4.25 2L15 21");
}

</style>
