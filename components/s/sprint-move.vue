<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m9vst9y2j"/><path class="o-24sv-rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sprint-move" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m9vst9y2j {
  d: path("M6.875 3.5h10.25A4.375 4.375 0 0 1 21.5 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 16.125v-8.25A4.375 4.375 0 0 1 6.875 3.5M12 3.5v17");
}

.o-24sv-rf {
  d: path("M7 7h.5a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 7.5 12H7a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 7 7m7.75 2.5h4m-2-2l2 2l-2 2");
}

</style>
