<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p3f03tbmh"/><path class="acja6ya7a"/><path class="j9kdj-bfk"/><path class="zoz5ar7wf"/><path class="ke4ug0b-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:student-duotone-thin" /></template>
<style>
.acja6ya7a {
  fill: currentColor;
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9kdj-bfk {
  d: path("m4 7 3 -3h10l3 3 -3 3H7Z");
}

.ke4ug0b-p {
  d: path("M7.5 21a4.5 4.5 0 0 1 9 0");
}

.p3f03tbmh {
  fill: currentColor;
  d: path("m4 7 3 -3h10l3 3 -3 3H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zoz5ar7wf {
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
