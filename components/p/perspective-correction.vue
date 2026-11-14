<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t-hzxabol"/><path class="j4m4x_lde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:perspective-correction" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4m4x_lde {
  d: path("M10.5 7h3A1.5 1.5 0 0 1 15 8.5V16a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 16V8.5A1.5 1.5 0 0 1 10.5 7");
}

.t-hzxabol {
  d: path("M5.147 20.5h13.706a1.75 1.75 0 0 0 1.714-2.103l-2.779-13.5A1.75 1.75 0 0 0 16.074 3.5H7.926a1.75 1.75 0 0 0-1.714 1.397l-2.779 13.5A1.75 1.75 0 0 0 5.147 20.5");
}

</style>
