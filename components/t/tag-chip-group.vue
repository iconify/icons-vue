<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utgmoq5zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tag-chip-group" /></template>
<style>
.utgmoq5zb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5h13a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-13a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Zm0 9H10a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3.5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Zm11.25 0h5.75a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5.75a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Zm-9.25-6h.01m-.01 9h.01m11.24 0h.01");
}

</style>
