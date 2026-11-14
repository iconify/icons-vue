<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq7diacyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-missing" /></template>
<style>
.qq7diacyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3.5C9.5 3.25 8.75 3 8 3C5.75 3 4.5 4.25 4 6.25m.25 3.5C4.75 12 5.75 13.5 6.5 15l.5 2.5m.5 2.75c.25 1 1.75 1 2-.25l.5-2.25M11 15c.75-.5 1.25-.5 2 0m1 2.75l.5 2.25c.25 1.25 1.5 1.25 2 .25m.5-2.75l.5-2.5c.75-1.5 1.75-3 2.25-5.25m.25-3.5c-.5-2-1.75-3.25-4-3.25c-.75 0-1.5.25-2.5.5");
}

</style>
