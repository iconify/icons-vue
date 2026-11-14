<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6sjh2b8u"/><path class="uuf418cat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reporting-line" /></template>
<style>
.e6sjh2b8u {
  d: path("M14.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M14 11c0-1.75 1.25-2.75 3-2.75s3 1 3 2.75Zm-9.25 2.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M4 20c0-1.75 1.25-2.75 3-2.75s3 1 3 2.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuf418cat {
  d: path("M7 11.5V4.75h7.75");
}

</style>
