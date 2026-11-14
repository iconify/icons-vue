<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpwo4qumh"/><path class="bmjkoed4r"/><path class="nlqchlbqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smartphone-rotate" /></template>
<style>
.bmjkoed4r {
  d: path("m8.5 19.5l-2 .25l.5 2m.25-18a9.5 9.5 0 0 1 10.25.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nlqchlbqk {
  d: path("m15.5 4.5l2-.25l-.5-2");
}

.zpwo4qumh {
  d: path("M11.5 6.5h1A3.5 3.5 0 0 1 16 10v4a3.5 3.5 0 0 1-3.5 3.5h-1A3.5 3.5 0 0 1 8 14v-4a3.5 3.5 0 0 1 3.5-3.5m5.25 13.75a9.5 9.5 0 0 1-10.25-.5");
}

</style>
