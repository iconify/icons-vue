<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryr6_tbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sound-barrier" /></template>
<style>
.ryr6_tbry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 2.5h5v19h-5ZM4.214 8.17a5 5 0 0 1 0 7.66M7.106 4.723a9.5 9.5 0 0 1 0 14.554");
}

</style>
