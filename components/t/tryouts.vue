<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5qbn_bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tryouts" /></template>
<style>
.n5qbn_bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1 4.5l-1 5l3 3v4.5m-3-7.5l-2.5 3.5V21m-.5-10l4-2l3 2.5m5.5-7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1 4.5l-1 5l3 3v4.5m-3-7.5l-2.5 3.5V21m-.5-10l4-2l3 2.5");
}

</style>
