<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wtqdu_amj"/><path class="bhhzfqb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-baby" /></template>
<style>
.bhhzfqb1k {
  d: path("M16 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wtqdu_amj {
  d: path("M8.5 4.25C7.25 3 3.25 2.75 3.25 6.5C3.25 8.75 4.5 10 5 12.25L5.5 14c.25 1 1.5 1 1.75 0L8 12c.25-.5.75-.5 1 0l.75 2c.25 1 1.5 1 1.75 0l.5-1.75c.5-2.25 1.75-3.5 1.75-5.75c0-3.75-4-3.5-5.25-2.25M16.75 17v-1.25a1.25 1.25 0 0 1 2.5 0V17m-4.5 0h6.5");
}

</style>
