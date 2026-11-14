<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f2rauu0hm"/><path class="p1plyib9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tyre-burnout" /></template>
<style>
.f2rauu0hm {
  d: path("M8.75 10a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1plyib9e {
  d: path("M12 10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m-2 11H6a2 2 0 1 1 2-2m-1.25-5h-2.5a2 2 0 1 1 2-2");
}

</style>
