<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-7co39ia"/><path class="j92r4yb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:super-clamp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j92r4yb5y {
  d: path("M9.75 12.5h9.5A1.75 1.75 0 0 1 21 14.25A1.75 1.75 0 0 1 19.25 16h-9.5A1.75 1.75 0 0 1 8 14.25a1.75 1.75 0 0 1 1.75-1.75M11 4v8.5M8.5 4h5");
}

.v-7co39ia {
  d: path("M15 7.5H7A3.5 3.5 0 0 0 3.5 11v5.5A3.5 3.5 0 0 0 7 20h8");
}

</style>
