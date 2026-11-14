<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nedyryuud"/><path class="d8t6wnxxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reveal" /></template>
<style>
.d8t6wnxxe {
  d: path("M9.25 14.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M12 2.5v3M5.5 4L7 6.5M18.5 4L17 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nedyryuud {
  d: path("M2.5 14.5C4.5 11 8 9 12 9s7.5 2 9.5 5.5C19.5 18 16 20 12 20s-7.5-2-9.5-5.5");
}

</style>
