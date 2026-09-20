<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="orvo1eb_t"/><path clip-rule="evenodd" class="wks47_kxb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zee-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.orvo1eb_t {
  fill: var(--svg-color--1741c3, #1741c3);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wks47_kxb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.889 12.057V7.133a5.77 5.77 0 0 0-2.667 4.87c0 1.768.794 3.35 2.045 4.41l.064-.051c2.548-2.091 5.226-4.289 5.693-4.624c.519-.373 1.07-.108 1.087.22v4.914a5.77 5.77 0 0 0 2.666-4.87a5.77 5.77 0 0 0-2.063-4.425c-2.61 2.077-5.4 4.265-5.87 4.604c-.688.493-.938.204-.955-.124m5.333 5.28v-4.446l-5.035 4.16a5.75 5.75 0 0 0 2.813.73c.787 0 1.538-.159 2.222-.444m-5.763.315a6.667 6.667 0 0 0 7.964-10.638a439 439 0 0 0 2.532-2.037c.118-.134.283-.48 0-.8s-.747-.134-.943 0l-2.584 2.107a6.667 6.667 0 0 0-7.858 10.7c-.933.767-1.815 1.49-2.525 2.068c-.118.133-.283.48 0 .801c.272.309.642.056.844-.082l.022-.015zm1.319-6.76V6.666A5.8 5.8 0 0 1 12 6.225c.97 0 1.885.24 2.689.662z");
}

</style>
