<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="apvpmjb4t"/><path class="uh0tthrbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:neck-collar" /></template>
<style>
.apvpmjb4t {
  d: path("M5.541 14.82C4.817 13.519 4.5 12.049 4.5 10.5C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H19v2.25q0 .155-.023.302");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uh0tthrbw {
  fill: currentColor;
  d: path("M8.25 16.75h6.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 6.5 18.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
