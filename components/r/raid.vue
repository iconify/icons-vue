<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxlf-3bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:raid" /></template>
<style>
.hxlf-3bse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM5.5 20.5c0-4 2.75-6.5 6-6.5q.294 0 .582.027M2.25 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m15 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M2.5 14c0-2 .75-3 2-3m15 0c.641 0 1.15.263 1.495.586M15 15l6.5 6.5m0-6.5L15 21.5m4.25-.25l2-2m-6 0l2 2");
}

</style>
