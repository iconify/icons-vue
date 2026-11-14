<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjlpou4md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:poll-multi-choice" /></template>
<style>
.xjlpou4md {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h12V7h-12Zm0 7.25h12v4.5h-12Zm0 7.25h12v4.5h-12Zm-7-12.5l2 2l3-3m-5 8.25l2 2l3-3");
}

</style>
