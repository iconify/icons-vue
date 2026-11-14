<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jk6k4ya2n"/><path class="ag462vp2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-collar" /></template>
<style>
.ag462vp2i {
  d: path("M6.25 12.75c-1.65.22-3.05-.12-3.75-1.25c1.05-.62 2.45-.62 3.5 0m6.25 1.25c1.45.22 2.85-.12 3.5-1.25c-1-.62-2.4-.62-3.5 0M7.5 11c-.1-1-.45-1.7-1.5-2m5 2c-.1-1 .25-1.7 1.25-2m2.25-3a3 3 0 0 1 3 3m-3-6.5A6.5 6.5 0 0 1 21 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jk6k4ya2n {
  d: path("m6.75 16.75l-.75-5a.75.75 0 0 1 .75-.75h4.75a.75.75 0 0 1 .75.75l-.75 5m-4.125 0h3.5A2.125 2.125 0 0 1 13 18.875A2.125 2.125 0 0 1 10.875 21h-3.5a2.125 2.125 0 0 1-2.125-2.125a2.125 2.125 0 0 1 2.125-2.125");
}

</style>
