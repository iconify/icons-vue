<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2x0lmbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:symmetry-guide" /></template>
<style>
.e2x0lmbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 12v5.25A1.75 1.75 0 0 1 7.5 19H5.492a1.75 1.75 0 0 1-1.587-2.487l2.397-5.164A1.546 1.546 0 0 1 9.25 12m5.5 0v5.25A1.75 1.75 0 0 0 16.5 19h2.008a1.75 1.75 0 0 0 1.587-2.487l-2.397-5.164A1.546 1.546 0 0 0 14.75 12M12 2.5v19");
}

</style>
