<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lbbboouyd"/><path class="hy3vmwbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:save-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hy3vmwbry {
  d: path("M8 4v3a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V4m-.25 14l2 2L21 15.75");
}

.lbbboouyd {
  d: path("M7.5 4h7.55a3.5 3.5 0 0 1 2.475 1.025l1.45 1.45A3.5 3.5 0 0 1 20 8.95v.925a2.375 2.375 0 0 1-2.375 2.375H15.75a3.5 3.5 0 0 0-3.5 3.5v.75a3.5 3.5 0 0 1-3.5 3.5H7.5A3.5 3.5 0 0 1 4 16.5v-9A3.5 3.5 0 0 1 7.5 4");
}

</style>
