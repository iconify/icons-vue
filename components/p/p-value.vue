<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xspv39b6q"/><path class="bklxxxpba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:p-value" /></template>
<style>
.bklxxxpba {
  fill: currentColor;
  d: path("M15 10c1.75 4 3.25 9.5 6.5 9.5H15Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xspv39b6q {
  d: path("M2.5 19.5c5 0 6-13 9.5-13s4.5 13 9.5 13");
}

</style>
