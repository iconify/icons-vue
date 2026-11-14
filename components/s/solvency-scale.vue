<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a46dzygvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solvency-scale" /></template>
<style>
.a46dzygvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v16m-4 0h8M5 7h14M2.75 13L5 7l2.25 6c0 1.25-1 2-2.25 2s-2.25-.75-2.25-2Zm14 0L19 7l2.25 6c0 1.25-1 2-2.25 2s-2.25-.75-2.25-2Z");
}

</style>
