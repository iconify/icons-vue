<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rzyzgqcqn"/><path class="jpsy3j9-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:particle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpsy3j9-d {
  d: path("M15.18 8.82q.55-3.03 3.71-3.71m-3.71 10.07q.55 3.03 3.71 3.71M8.82 15.18q-.55 3.03-3.71 3.71M8.82 8.82q-.55-3.03-3.71-3.71");
}

.rzyzgqcqn {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

</style>
