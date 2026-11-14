<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0fx0dkgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pharmacy-basket" /></template>
<style>
.b0fx0dkgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19L19 20.5H5Zm1.25 0a4.25 4.25 0 0 1 8.5 0M15 12V8.5A1.5 1.5 0 0 1 16.5 7h2A1.5 1.5 0 0 1 20 8.5V12m-4.25-8.5h3.5V7h-3.5Z");
}

</style>
