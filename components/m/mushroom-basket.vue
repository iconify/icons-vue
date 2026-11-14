<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qq1po1bwz"/><path class="ms_7rjb5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mushroom-basket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ms_7rjb5n {
  d: path("M8.5 15.5a3.5 3.5 0 0 1 7 0Zm3.5 0v2.25");
}

.qq1po1bwz {
  d: path("M5.645 9.5h12.71a2.625 2.625 0 0 1 2.582 3.095l-1.045 5.75a2.625 2.625 0 0 1-2.583 2.155H6.691a2.625 2.625 0 0 1-2.583-2.155l-1.045-5.75A2.625 2.625 0 0 1 5.645 9.5M7 9.5l3-6m7 6l-3-6");
}

</style>
