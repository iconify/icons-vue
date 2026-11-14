<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ljdtb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:primary-key" /></template>
<style>
.j_ljdtb3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm6 2.5L20 20m-4-4l2.5-2.5M18 18l2.5-2.5");
}

</style>
