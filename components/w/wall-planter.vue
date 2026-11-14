<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5ws48bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wall-planter" /></template>
<style>
.p5ws48bye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H6v19H2.5Zm3.5 10h14.5v6H6Zm0 9l4-3m3.25-6V5m0 5C10.5 10 9 8.5 9 6c2.75 0 4.25 1.5 4.25 4m0-1C16 9 17.5 7.5 17.5 5c-2.75 0-4.25 1.5-4.25 4");
}

</style>
