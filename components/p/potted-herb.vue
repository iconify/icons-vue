<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmekh89hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potted-herb" /></template>
<style>
.qmekh89hy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 14.5h13l-1.75 7h-9.5Zm6.5 0V7m0 0c-1.75-1.5-1.75-3.25 0-4.5c1.75 1.25 1.75 3 0 4.5Zm0 2.5C9 8 6 8.5 4.5 11c2.5 1 5.5.5 7.5-1.5Zm0 0c3-1.5 6-1 7.5 1.5c-2.5 1-5.5.5-7.5-1.5Z");
}

</style>
