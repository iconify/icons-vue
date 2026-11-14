<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtuecs9vi"/><path class="tatk-wg_u"/><path class="d_0difb6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:next-of-kin" /></template>
<style>
.d_0difb6p {
  fill: currentColor;
  d: path("M16.5 15s-2.75-1.75-2.75-3.5c0-1 .75-1.75 1.5-1.75c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c.75 0 1.5.75 1.5 1.75c0 1.75-2.75 3.5-2.75 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mtuecs9vi {
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 5");
}

.tatk-wg_u {
  d: path("M6 9.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4.75 16c0-1.75 1.5-2.75 3.25-2.75s3.25 1 3.25 2.75");
}

</style>
