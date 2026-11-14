<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1p01s2ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thumbs-down" /></template>
<style>
.w1p01s2ra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17 13l-3.5 6.5c-1 1.5-3.5 1-3.25-1.25l.5-3.75H5.5a2 2 0 0 1-2-2.25l1.25-6.5a2 2 0 0 1 2-1.75H17Zm1.5-9h3v9.5h-3Z");
}

</style>
