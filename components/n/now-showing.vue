<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft1bqobpo"/><path class="q5uv-om9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:now-showing" /></template>
<style>
.ft1bqobpo {
  d: path("M4.5 5.5h15A1.5 1.5 0 0 1 21 7v3a2 2 0 0 0 0 4v3a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 17v-3a2 2 0 0 0 0-4V7a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q5uv-om9j {
  d: path("m11.756 9.816l1.523.888a1.5 1.5 0 0 1 0 2.592l-1.523.888A1.5 1.5 0 0 1 9.5 12.888v-1.776a1.5 1.5 0 0 1 2.256-1.296");
}

</style>
