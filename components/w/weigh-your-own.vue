<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvernjo8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weigh-your-own" /></template>
<style>
.fvernjo8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12.5h17m-8.5 0v3m-7.5 0h15v6h-15ZM12 5.75c-1.25-1-4.75-1-4.75 2.5c0 2.5 1.75 4.25 3.25 4.25h3c1.5 0 3.25-1.75 3.25-4.25c0-3.5-3.5-3.5-4.75-2.5Zm0 0L13 3");
}

</style>
