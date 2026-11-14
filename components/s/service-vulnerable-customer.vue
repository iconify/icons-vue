<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g99ep4bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:service-vulnerable-customer" /></template>
<style>
.g99ep4bdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM4 21c0-4 3.5-6.5 8-6.5q.444 0 .875.032M18 21c-1.5-1-3-2.25-3-4c0-1 .75-1.75 1.75-1.75c.65 0 1.05.35 1.25.75c.2-.4.6-.75 1.25-.75c.95 0 1.75.75 1.75 1.75c0 1.75-1.5 3-3 4Z");
}

</style>
