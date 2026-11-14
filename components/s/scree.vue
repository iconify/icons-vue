<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpq2j_b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scree" /></template>
<style>
.lpq2j_b5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5L4 15l4.5-1.5l2 3.5l-1 3.5Zm10.5 0l.5-4.5l4-3l4 3.5l-.5 4Zm-6-12L10.5 4L16 6l-.5 3.75l-4.5.5Z");
}

</style>
