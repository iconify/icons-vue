<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d9ntutbyz"/><path class="q4jdjlb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-ripple" /></template>
<style>
.d9ntutbyz {
  d: path("M12 2.5S8.25 6.75 8.25 9.25a3.75 3.75 0 0 0 7.5 0C15.75 6.75 12 2.5 12 2.5M7 16.25a5 2 0 0 0 10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q4jdjlb3g {
  d: path("M2.5 16.5a9.5 4.5 0 0 0 19 0");
}

</style>
