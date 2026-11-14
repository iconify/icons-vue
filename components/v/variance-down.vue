<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyy0bpb4s"/><path class="tjf6ufb_o"/><path class="l9v88dq3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:variance-down" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9v88dq3g {
  d: path("M2.5 21.5h19M11.5 5H13m2.5 0H17m2.5 0H21m-4.75 1.75V10M14.5 8.25L16.25 10L18 8.25");
}

.tjf6ufb_o {
  fill: currentColor;
  d: path("M15 12h2.5a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5H15a1.5 1.5 0 0 1-1.5-1.5v-6.5A1.5 1.5 0 0 1 15 12");
}

.yyy0bpb4s {
  d: path("M6 5h2.5A1.5 1.5 0 0 1 10 6.5V20a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20V6.5A1.5 1.5 0 0 1 6 5");
}

</style>
