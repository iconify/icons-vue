<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="k3q37cbyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sneezing-face" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3q37cbyn {
  d: path("M7.5 8.5L10 9.75L7.5 11m9-2.5L14 9.75L16.5 11M10 13.5h4q1 0 1.66.75l.43.5q.66.75 0 1.5l-.43.5q-.66.75-1.66.75h-4q-1 0-1.66-.75l-.43-.5q-.66-.75 0-1.5l.43-.5Q9 13.5 10 13.5");
}

</style>
