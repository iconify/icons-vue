<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d85x_ikfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:server-download" /></template>
<style>
.d85x_ikfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h18V8H3Zm0 8.25h18v5.5H3Zm3.5-5.5h.01M6.5 13.5h.01M12 16.25v5.25M9.5 19l2.5 2.5l2.5-2.5");
}

</style>
