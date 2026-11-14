<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rwz_uil5u"/><path class="tjth2nzla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:substitution-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rwz_uil5u {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v5a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 12V7A3.5 3.5 0 0 1 6 3.5m6 12V21m0-17.5v12");
}

.tjth2nzla {
  d: path("M5.5 6.25h3.75l-2 6.5m7.5-5.25l2-1.25v6.5");
}

</style>
