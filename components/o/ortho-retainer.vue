<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kgi25o6dd"/><path class="vp7oxebgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ortho-retainer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kgi25o6dd {
  d: path("M4.5 19v-5.5a7.5 7.5 0 0 1 15 0V19a2 2 0 0 1-4 0v-5.5a3.5 3.5 0 0 0-7 0V19a2 2 0 0 1-4 0");
}

.vp7oxebgj {
  d: path("M3 8.5a10.25 10.25 0 0 1 18 0M12 6v3.75m5.25-1.5L14.5 11M6.75 8.25L9.5 11");
}

</style>
