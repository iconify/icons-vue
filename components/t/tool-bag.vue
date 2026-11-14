<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jepnn6bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tool-bag" /></template>
<style>
.jepnn6bjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h17v9a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2ZM8 10V7a4 4 0 0 1 8 0v3M3.5 14.5h17");
}

</style>
