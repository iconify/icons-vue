<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="avtz9wyas"/><path class="dylpou2wd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tent-check" /></template>
<style>
.avtz9wyas {
  d: path("m12.71 5.32l7.33 13.61q.71 1.32-.79 1.32H4.75q-1.5 0-.79-1.32l7.33-13.61q.71-1.32 1.42 0");
}

.dylpou2wd {
  d: path("m12.24 12.21l2.52 7.33q.24.71-.51.71h-4.5q-.75 0-.51-.71l2.52-7.33q.24-.71.48 0M10.5 2.75L12 4l1.5-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
