<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wvoe18bao"/><path class="o9euixbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:washing-machine-open" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9euixbrm {
  d: path("M5.25 14a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M17 14a2 4.5 0 1 0 4 0a2 4.5 0 1 0-4 0");
}

.wvoe18bao {
  d: path("M6 2.5h5A3.5 3.5 0 0 1 14.5 6v12a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18V6A3.5 3.5 0 0 1 6 2.5M2.5 7h12");
}

</style>
