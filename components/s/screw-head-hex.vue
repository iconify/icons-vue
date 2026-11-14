<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7qjn6psg"/><path class="ob7qoxbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:screw-head-hex" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7qjn6psg {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0");
}

.ob7qoxbjm {
  d: path("m14.933 8.42l1.634 2.83a1.5 1.5 0 0 1 0 1.5l-1.634 2.83a1.5 1.5 0 0 1-1.299.75h-3.268a1.5 1.5 0 0 1-1.299-.75l-1.634-2.83a1.5 1.5 0 0 1 0-1.5l1.634-2.83a1.5 1.5 0 0 1 1.299-.75h3.268a1.5 1.5 0 0 1 1.299.75");
}

</style>
