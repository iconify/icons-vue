<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p0fgzs8ji"/><path class="j1jcv9bug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:turbo-roundabout" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1jcv9bug {
  d: path("M21 16.5v3h-3M3 7.5v-3h3");
}

.p0fgzs8ji {
  d: path("M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12 6.5a6 6 0 0 1 6 6q0 4 3 7m-9-2a6 6 0 0 1-6-6q0-4-3-7");
}

</style>
