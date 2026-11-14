<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwo04zrgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tag-chip-close" /></template>
<style>
.uwo04zrgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5h13A3.5 3.5 0 0 1 22 10v4a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 14v-4a3.5 3.5 0 0 1 3.5-3.5ZM6 12h5.5m3.5-1.75l3.5 3.5m0-3.5l-3.5 3.5");
}

</style>
