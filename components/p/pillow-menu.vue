<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjkpicc_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pillow-menu" /></template>
<style>
.kjkpicc_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.25c4.25 2 12.25 2 16.5 0c-2 3.25-2 6.25 0 9.5c-4.25-2-12.25-2-16.5 0C5 9.5 5 6.5 3 3.25Zm12.5 12.5h6m-6 3h6m-6 3h4");
}

</style>
