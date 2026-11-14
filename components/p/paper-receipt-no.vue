<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snigsbctg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paper-receipt-no" /></template>
<style>
.snigsbctg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.9 3H19v12.1m-3.82 4.083L12 21l-3.5-2L5 21V8.925M11.4 7.5h4.1m-.6 3.5h.6m-12-7.5l17 17");
}

</style>
