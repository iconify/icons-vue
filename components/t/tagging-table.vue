<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjv9xmb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tagging-table" /></template>
<style>
.bjv9xmb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5h19v3h-19Zm2.5 3v11m14-11v11m-7-11V13m-2.5 2.5L12 13l2.5 2.5v5h-5Zm2.5.25h.01M6 3h6v4.5H6Z");
}

</style>
