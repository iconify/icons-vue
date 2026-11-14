<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uw9v-nb9x"/><path class="fm8gnsb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:t-test" /></template>
<style>
.fm8gnsb4f {
  d: path("M9 20.5c3.5 0 4-11 6.5-11s3 11 6.5 11M9 4.5h6m-4.25-1.75L9 4.5l1.75 1.75m2.5-3.5L15 4.5l-1.75 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uw9v-nb9x {
  d: path("M2 20.5c3.5 0 4-11 6.5-11s3 11 6.5 11");
}

</style>
