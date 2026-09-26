<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mfuhg6upf"/><path class="blri9wbom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-sharp-fill" /></template>
<style>
.blri9wbom {
  d: path("M4 5L1 5M20 5L23 5M7 18L4.7236 22.5528M17 18L19.2764 22.5528");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mfuhg6upf {
  fill: currentColor;
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 18C21 18.5523 20.5523 19 20 19L4 19C3.4477 19 3 18.5523 3 18L3 2C3 1.4477 3.4477 1 4 1ZM5 3L5 8L19 8L19 3L5 3ZM10 13.5C10 12.6716 9.3284 12 8.5 12C7.6716 12 7 12.6716 7 13.5C7 14.3284 7.6716 15 8.5 15C9.3284 15 10 14.3284 10 13.5ZM17 13.5C17 12.6716 16.3284 12 15.5 12C14.6716 12 14 12.6716 14 13.5C14 14.3284 14.6716 15 15.5 15C16.3284 15 17 14.3284 17 13.5Z");
  stroke: none;
}

</style>
