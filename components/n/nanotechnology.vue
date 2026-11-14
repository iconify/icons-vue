<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u6kribbcg"/><path class="zi18sob-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nanotechnology" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u6kribbcg {
  d: path("M5.875 3.25h4.75a2.625 2.625 0 0 1 2.625 2.625v4.75a2.625 2.625 0 0 1-2.625 2.625h-4.75a2.625 2.625 0 0 1-2.625-2.625v-4.75A2.625 2.625 0 0 1 5.875 3.25m2.375 10v4.5h6.5m0 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.zi18sob-a {
  d: path("M7.75 6.25h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
