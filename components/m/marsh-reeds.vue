<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v0monbdeo"/><path class="curbr4b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marsh-reeds" /></template>
<style>
.curbr4b5o {
  d: path("M2.5 19.5q2.375-1.25 4.75 0t4.75 0t4.75 0t4.75 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0monbdeo {
  d: path("M12 19.5V11m0-6.5v-2m0 2zA1.5 1.5 0 0 1 13.5 6v3.5A1.5 1.5 0 0 1 12 11a1.5 1.5 0 0 1-1.5-1.5V6A1.5 1.5 0 0 1 12 4.5m-2.75 15C9 14 7 9.5 3.5 7m11.25 12.5C15 14 17 9.5 20.5 7");
}

</style>
