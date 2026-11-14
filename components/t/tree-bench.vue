<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9oqvelly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tree-bench" /></template>
<style>
.n9oqvelly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12a3 3 0 0 1 1-5.75a4 4 0 0 1 8 0A3 3 0 0 1 17 12Zm5 0v3m-9 2a9 2 0 1 0 18 0a9 2 0 1 0-18 0m2 1.25v3.25m7-2.5v2.5m7-3.25v3.25");
}

</style>
