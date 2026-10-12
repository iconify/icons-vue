<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="io73-qbng"/><path class="j5d-ujy9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:module-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.io73-qbng {
  d: path("m13.08 3.89l3.34 1.97q1.08.64 1.08 1.89v8.5q0 1.25-1.08 1.89l-3.34 1.97q-1.08.64-2.16 0l-3.34-1.97Q6.5 17.5 6.5 16.25v-8.5q0-1.25 1.08-1.89l3.34-1.97q1.08-.64 2.16 0");
}

.j5d-ujy9l {
  d: path("M7.25 7L12 9.75L16.75 7M12 9.75V20m-9.25-8h1.5m15.5 0h1.5");
}

</style>
