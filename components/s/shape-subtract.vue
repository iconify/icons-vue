<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa8u9hbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shape-subtract" /></template>
<style>
.oa8u9hbmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3h7A2.5 2.5 0 0 1 15 5.5V9H9v6H5.5A2.5 2.5 0 0 1 3 12.5v-7A2.5 2.5 0 0 1 5.5 3Zm11.75 6h1.25a2.5 2.5 0 0 1 2.5 2.5v1.25m0 3.5v2.25a2.5 2.5 0 0 1-2.5 2.5h-2.25m-3.5 0H11.5A2.5 2.5 0 0 1 9 18.5v-1.25");
}

</style>
