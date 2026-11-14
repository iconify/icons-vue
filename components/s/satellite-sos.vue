<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtba4ebvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-sos" /></template>
<style>
.rtba4ebvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3h5v7h-5Zm-6 .5h4v6h-4Zm13 0h4v6h-4Zm-9 3h2m5 0h2m-6.75 7.25a3 3 0 0 0 4.5 0m-6.5 2a6 6 0 0 0 8.5 0M18 14.5V18m0 3h.01");
}

</style>
