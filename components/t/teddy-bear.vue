<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="elimv7bkp"/><path class="xy83m1bta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:teddy-bear" /></template>
<style>
.elimv7bkp {
  d: path("M4.5 13a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xy83m1bta {
  d: path("M5.544 9.222a2.75 2.75 0 1 1 3.849-3.23m5.214 0a2.75 2.75 0 1 1 3.849 3.23M9.5 15.75a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0m-.25-4.25h.01m5.49 0h.01");
}

</style>
