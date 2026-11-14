<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6r8h-b7m"/><path class="zxuhvovba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-valuation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q6r8h-b7m {
  d: path("m3.013 10.487l4.25-4.25a1.75 1.75 0 0 1 2.474 0l4.25 4.25a1.75 1.75 0 0 1 .513 1.238v7.525A1.75 1.75 0 0 1 12.75 21h-8.5a1.75 1.75 0 0 1-1.75-1.75v-7.525a1.75 1.75 0 0 1 .513-1.238M18.25 13.25h1.5a1.5 1.5 0 0 1 1.5 1.5v3.379a1.5 1.5 0 0 1-.439 1.06l-.75.75a1.5 1.5 0 0 1-2.122 0l-.75-.75a1.5 1.5 0 0 1-.439-1.06V14.75a1.5 1.5 0 0 1 1.5-1.5M12.5 9l4.25 4.25m2.25 2.5h.01");
}

.zxuhvovba {
  d: path("M6.5 21v-3.5a2 2 0 0 1 4 0V21");
}

</style>
