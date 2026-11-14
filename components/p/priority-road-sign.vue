<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u-s9u8vws"/><path class="aprtz6b4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:priority-road-sign" /></template>
<style>
.aprtz6b4q {
  d: path("m13.237 6.737l4.026 4.026a1.75 1.75 0 0 1 0 2.474l-4.026 4.026a1.75 1.75 0 0 1-2.474 0l-4.026-4.026a1.75 1.75 0 0 1 0-2.474l4.026-4.026a1.75 1.75 0 0 1 2.474 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u-s9u8vws {
  d: path("M7.75 2.5h8.5a5.25 5.25 0 0 1 5.25 5.25v8.5a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25v-8.5A5.25 5.25 0 0 1 7.75 2.5");
}

</style>
