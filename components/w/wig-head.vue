<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3ompm1ke"/><path class="dpizxebqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wig-head" /></template>
<style>
.dpizxebqj {
  d: path("M6.41 19a3.52 3.52 0 0 1-1.73-4.05a3.64 3.64 0 0 1 .14-4.55A3.49 3.49 0 0 1 6.8 6.52a3.19 3.19 0 0 1 3.3-2.23a3.03 3.03 0 0 1 3.8 0a3.19 3.19 0 0 1 3.3 2.23a3.49 3.49 0 0 1 1.98 3.88a3.64 3.64 0 0 1 .14 4.55A3.52 3.52 0 0 1 17.59 19M10 18.4V21m4-2.6V21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y3ompm1ke {
  d: path("M12 7a4.5 6 0 1 0 0 12a4.5 6 0 1 0 0-12");
}

</style>
