<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bc9l0dh9l"/><circle class="o1ytxaclq"/><path class="q27yk5b4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:student-check" /></template>
<style>
.bc9l0dh9l {
  d: path("m12.95 3.06l5.1 1.63q.95.31 0 .62l-5.1 1.63q-.95.31-1.9 0l-5.1-1.63Q5 5 5.95 4.69l5.1-1.63q.95-.31 1.9 0M19 5v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1ytxaclq {
  cx: 12px;
  cy: 12.25px;
  r: 2.25px;
}

.q27yk5b4f {
  d: path("M5 21.25h14a1 1 0 0 0 1-1c0-2-3.6-3.25-8-3.25s-8 1.25-8 3.25a1 1 0 0 0 1 1");
}

</style>
