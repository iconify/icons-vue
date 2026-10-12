<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lu6idjaig"/><path class="o1cbt2b5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lu6idjaig {
  d: path("M5.42 18.5c-.7-4.21 4.93-7.46 8.66-5c.27 4.46-5.36 7.71-8.66 5");
}

.o1cbt2b5y {
  d: path("M7.62 17.81c.89-1.96 2.62-2.96 4.76-2.75m1.7-1.56c1.5-1 2.25-2.75 1.75-5m-.23 0c.5-2.25 2.25-3.75 4.75-4c0 2.5-1.75 4-4.75 4");
}

</style>
