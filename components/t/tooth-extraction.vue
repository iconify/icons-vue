<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chinzieet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-extraction" /></template>
<style>
.chinzieet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.25c-1.5 0-2 1.25-2 3s1 3 1.5 4.75l.5 2.5c.25.75 1.25.75 1.5 0l.5-2.5c.5-.5 1.5-.5 2 0l.5 2.5c.25.75 1.25.75 1.5 0L12 14c.5-1.75 1.5-3 1.5-4.75s-.5-3-2-3c-1.25 0-1.75.5-3 .5s-1.75-.5-3-.5ZM2.5 20h1q5 3.5 10 0h8m-3-4V3m-2.75 2.75L18.5 3l2.75 2.75");
}

</style>
