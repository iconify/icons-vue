<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vywi_db0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signpost" /></template>
<style>
.vywi_db0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5h12.5L20 7.5L17.5 10H5Zm14 7.5H6.5L4 15l2.5 2.5H19Zm-7-10V5m0 5v2.5m0 5v4");
}

</style>
