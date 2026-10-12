<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x8gsxpbag"/><path class="yslorpc4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zodiac-scorpio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8gsxpbag {
  d: path("M3.75 6.5C5.25 6.5 6 7.5 6 9v11.25M6 9c0-1.5 1-2.5 2.5-2.5S11 7.5 11 9v11.25M11 9c0-1.5 1-2.5 2.5-2.5S16 7.5 16 9v7c0 1.5.75 2.5 2.25 2.5h2.25");
}

.yslorpc4u {
  d: path("m18.5 16.25l2.25 2.25l-2.25 2.25");
}

</style>
