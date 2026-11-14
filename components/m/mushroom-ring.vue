<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqq7c1boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mushroom-ring" /></template>
<style>
.qqq7c1boc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5a2.5 2.5 0 0 1 5 0Zm2.5 0V8m4.25 2.25a2.5 2.5 0 0 1 5 0Zm2.5 0v2.5m-5.25 5.5a2.5 2.5 0 0 1 5 0Zm2.5 0v2.5m-10.5-2.5a2.5 2.5 0 0 1 5 0Zm2.5 0v2.5m-5.25-10.5a2.5 2.5 0 0 1 5 0Zm2.5 0v2.5");
}

</style>
