<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faauy035n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:select-all" /></template>
<style>
.faauy035n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7V5.5a2 2 0 0 1 2-2H7m10 0h1.5a2 2 0 0 1 2 2V7m0 10v1.5a2 2 0 0 1-2 2H17m-10 0H5.5a2 2 0 0 1-2-2V17m7-13.5h3m-3 17h3m-10-10v3m17-3v3M8 8h8v8H8Z");
}

</style>
