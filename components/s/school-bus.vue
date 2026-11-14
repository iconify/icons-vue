<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sabtjqbjk"/><path class="a2z5i_nhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:school-bus" /></template>
<style>
.a2z5i_nhx {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sabtjqbjk {
  d: path("M2.5 16.5V7a2 2 0 0 1 2-2h12c1.25 0 2.1.75 2.5 1.75L21.5 12v4.5Zm0-6H20M8 5v5.5M13.5 5v5.5");
}

</style>
