<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xf1m88tri"/><path class="xass30bzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-backpacker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xass30bzm {
  d: path("M8.5 13.5v-4h7v4");
}

.xf1m88tri {
  d: path("M5.5 16.5V8a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v8.5M9.5 5a2.5 2.5 0 0 1 5 0m-9 11.5h13A2.5 2.5 0 0 1 21 19a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 19a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
