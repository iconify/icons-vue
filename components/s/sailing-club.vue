<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ly88glb7f"/><path class="febfkcgtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sailing-club" /></template>
<style>
.febfkcgtn {
  d: path("M7.5 21.5v-4h3v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ly88glb7f {
  d: path("m4.013 12.487l3.75-3.75a1.75 1.75 0 0 1 2.474 0l3.75 3.75a1.75 1.75 0 0 1 .513 1.238v6.025a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75v-6.025a1.75 1.75 0 0 1 .513-1.238M19.5 2.5v19M17.329 3.835L17 4a1.398 1.398 0 0 0 0 2.5l.329.165A1.5 1.5 0 0 0 19.5 5.323v-.146a1.5 1.5 0 0 0-2.171-1.342");
}

</style>
