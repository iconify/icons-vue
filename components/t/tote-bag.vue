<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wfe69pb2d"/><path class="udtlu6bnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tote-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.udtlu6bnn {
  d: path("M7.75 9.25v-4.5a1.5 1.5 0 0 1 3 0v4.5m2.5 0v-4.5a1.5 1.5 0 0 1 3 0v4.5");
}

.wfe69pb2d {
  d: path("M7.25 9.25h9.5q1.5 0 1.69 1.49l1.12 9.02q.19 1.49-1.31 1.49H5.75q-1.5 0-1.31-1.49l1.12-9.02q.19-1.49 1.69-1.49");
}

</style>
