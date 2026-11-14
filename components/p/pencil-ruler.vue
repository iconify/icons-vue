<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_5rwnbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pencil-ruler" /></template>
<style>
.h_5rwnbbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h6.5v19H3Zm11 0h5.5v13L16.75 21L14 15.5ZM3 6h2.75M3 9.5h2M3 13h2.75M3 16.5h2M14 6h5.5M14 15.5h5.5");
}

</style>
