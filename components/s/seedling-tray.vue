<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jogywkbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seedling-tray" /></template>
<style>
.jogywkbbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19L20 19H4Zm5 0v-4m0 0c0-2.25-1.25-3.5-3-3.5c0 2.25 1.25 3.5 3 3.5Zm0 0c0-2.25 1.25-3.5 3-3.5c0 2.25-1.25 3.5-3 3.5Zm9 4v-4m0 0c0-2.25-1.25-3.5-3-3.5c0 2.25 1.25 3.5 3 3.5Zm0 0c0-2.25 1.25-3.5 3-3.5c0 2.25-1.25 3.5-3 3.5Z");
}

</style>
