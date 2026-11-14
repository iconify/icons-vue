<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cbeqyqb5f"/><path class="by58rgblo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-photo-album" /></template>
<style>
.by58rgblo {
  d: path("M13.5 9.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M4 17l5-5l4 4l2.5-2l4.5 4");
}

.cbeqyqb5f {
  d: path("M7.5 4.5h9A3.5 3.5 0 0 1 20 8v8a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 16V8a3.5 3.5 0 0 1 3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
