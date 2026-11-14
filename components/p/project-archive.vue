<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvdsg1bjo"/><path class="t7snhjbfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:project-archive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t7snhjbfx {
  d: path("m9.5 15l2.5 2.5l2.5-2.5");
}

.tvdsg1bjo {
  d: path("M4.75 4h14.5A1.75 1.75 0 0 1 21 5.75v1a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 6.75v-1A1.75 1.75 0 0 1 4.75 4M4.5 8.5v10a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-10M12 11.25v6.25");
}

</style>
