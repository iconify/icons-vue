<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwvv0gbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-baking" /></template>
<style>
.pwvv0gbcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 11V8.25A2.75 2.75 0 1 1 12 4a2.75 2.75 0 1 1 3.5 4.25V11Zm.25 0v1a3.25 3.25 0 0 0 6.5 0v-1M4 21.5c0-2.5 3.25-3.75 8-3.75q.416 0 .815.013m2.777 1.442l4.096-2.868l1.72 2.458l-4.096 2.868ZM15 21.5l1.25-1m4.5-3l1.25-1");
}

</style>
