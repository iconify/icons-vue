<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atmm15bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trail-running" /></template>
<style>
.atmm15bdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1.5 2L14 13m3 5l1-3l-4-2l-2.5 3l-.5 3.5m.5-8l1.25-2.75L17 9.5l2 2.5M2.5 16l4-5.5l2.5 3m-6 8L21 17");
}

</style>
