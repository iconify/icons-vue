<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdg_2nbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:press-coverage" /></template>
<style>
.fdg_2nbfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5H4.5a2 2 0 0 0-2 2v9a2 2 0 0 0 2 2H7m0-17h14.5v17H7Zm7.25 0h.01M10 7.5h8.5m-8.5 4h8.5m-8.5 4h5");
}

</style>
