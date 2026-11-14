<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0f74lbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:unit-conversion" /></template>
<style>
.a0f74lbxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 10l1 9A1.5 1.5 0 0 0 5 20.5h2A1.5 1.5 0 0 0 8.5 19l1-9m5 0l1 9a1.5 1.5 0 0 0 1.5 1.5h2a1.5 1.5 0 0 0 1.5-1.5l1-9M3 14h6m6.25 2.5h5.5M7 4.5h10M9.25 2.25L7 4.5l2.25 2.25m5.5-4.5L17 4.5l-2.25 2.25");
}

</style>
