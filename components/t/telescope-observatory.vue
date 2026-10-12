<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tqh305-3q"/><path class="kfly4m-6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:telescope-observatory" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfly4m-6x {
  d: path("M10.5 21.25V18.5a1.5 1.5 0 0 1 3 0v2.75m.02-12.54l4.71-4.92q.52-.54 1.05-.01l1.19 1.19q.53.53.01 1.07l-4.71 4.92q-.52.54-1.05.01l-1.19-1.19q-.53-.53-.01-1.07");
}

.tqh305-3q {
  d: path("M4 21.25V12.5a8 8 0 0 1 16 0v8.75Z");
}

</style>
