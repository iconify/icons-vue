<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kqizwybyw"/><path class="qyk_klboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:taste-buds" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqizwybyw {
  d: path("M3 6q9 5 18 0");
}

.qyk_klboo {
  d: path("M7 7.75v5.75a5 5 0 0 0 10 0V7.75m-5 3.5v4.25");
}

</style>
