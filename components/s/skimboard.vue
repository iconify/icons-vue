<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd7gscqqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skimboard" /></template>
<style>
.wd7gscqqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12.5c0-3 8-8 14-8c2.5 0 3 2 1.5 3.5c-3 2.5-12.5 6.5-14.5 6.5c-.5 0-1-1-1-2Zm-1.5 5h19M6 20.5h12");
}

</style>
