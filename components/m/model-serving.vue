<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cta7os4xk"/><path class="y7w15acbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:model-serving" /></template>
<style>
.cta7os4xk {
  d: path("m6.956 7.126l2.25 1.2A1.5 1.5 0 0 1 10 9.65v4.7a1.5 1.5 0 0 1-.794 1.324l-2.25 1.2a1.5 1.5 0 0 1-1.412 0l-2.25-1.2A1.5 1.5 0 0 1 2.5 14.35v-4.7a1.5 1.5 0 0 1 .794-1.324l2.25-1.2a1.5 1.5 0 0 1 1.412 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7w15acbq {
  d: path("m2.5 8.75l3.75 2l3.75-2m-3.75 2v6.5m6.5-5.25H17m-2-2l2 2l-2 2m3.75-4.25h1a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 17 12.5v-1a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
