<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0ujr_6og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tree-shade" /></template>
<style>
.k0ujr_6og {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM9 13v6m0 0a5.75 1.75 0 1 0 11.5 0A5.75 1.75 0 1 0 9 19Zm-5.5 0H9");
}

</style>
