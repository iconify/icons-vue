<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfnimsbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:printer-x" /></template>
<style>
.rfnimsbih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v10.5h-19Zm4 10.5v5a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1v-5m-8 3h5M10 7l4 4.5M14 7l-4 4.5");
}

</style>
