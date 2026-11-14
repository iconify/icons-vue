<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lr2--tbzu"/><path class="e9dvc23vw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-shelf" /></template>
<style>
.e9dvc23vw {
  d: path("M12 10.5V7.75c-.25-3-2.25-5-5.25-5c0 3 2.25 5 5.25 5c.25-3.25 2.25-5.25 5.25-5.25c0 3-2 5.25-5.25 5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lr2--tbzu {
  d: path("M2.5 16.5h19M4 16.5v4l3.5-4m12.5 0v4l-3.5-4m-7.155-6h5.31a1.5 1.5 0 0 1 1.469 1.806l-.625 3A1.5 1.5 0 0 1 14.03 16.5H9.97a1.5 1.5 0 0 1-1.469-1.194l-.625-3A1.5 1.5 0 0 1 9.345 10.5");
}

</style>
