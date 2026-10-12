<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="akmmmz6xk"/><path class="q0ml346ab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spire" /></template>
<style>
.akmmmz6xk {
  d: path("M8 20.65v-8.3q0-.6.24-1.15l3.52-7.9q.24-.55.48 0l3.52 7.9q.24.55.24 1.15v8.3q0 .6-.6.6H8.6q-.6 0-.6-.6M10.5 8.5h3M8 12.75h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0ml346ab {
  d: path("M10.5 19.25V17a1.5 1.5 0 0 1 3 0v2.25");
}

</style>
