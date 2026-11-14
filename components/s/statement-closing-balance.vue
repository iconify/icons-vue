<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="knz8k1bii"/><path class="sbh56mbug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:statement-closing-balance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knz8k1bii {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5M8 6.5h8M8 10h8");
}

.sbh56mbug {
  d: path("M8.75 13.5h6.5A1.75 1.75 0 0 1 17 15.25v1A1.75 1.75 0 0 1 15.25 18h-6.5A1.75 1.75 0 0 1 7 16.25v-1a1.75 1.75 0 0 1 1.75-1.75m.5 2.25h5.5");
}

</style>
