<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmqgagsie"/><path class="e9gub3b_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wall-outlet" /></template>
<style>
.e9gub3b_s {
  d: path("M7.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hmqgagsie {
  d: path("M10 3h4a7 7 0 0 1 7 7v4a7 7 0 0 1-7 7h-4a7 7 0 0 1-7-7v-4a7 7 0 0 1 7-7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
