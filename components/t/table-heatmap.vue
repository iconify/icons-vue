<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqxb1xehn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:table-heatmap" /></template>
<style>
.bqxb1xehn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17v17h-17Zm5.75 0v17m5.5-17v17M3.5 9.25h17m-17 5.5h17M6.25 6.25h.01M12 12h.01m5.49 5.5h.01M17.5 6.25h.01");
}

</style>
