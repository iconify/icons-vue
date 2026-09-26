<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qbi2l1bgh"/><path class="h39o2mrll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-2-vertical-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h39o2mrll {
  d: path("M7 2L7 7M7 13L7 22M17 2L17 11M17 17L17 22");
}

.qbi2l1bgh {
  fill: currentColor;
  d: path("M4.5 5L9.5 5C10.3284 5 11 5.6716 11 6.5L11 13.5C11 14.3284 10.3284 15 9.5 15L4.5 15C3.6716 15 3 14.3284 3 13.5L3 6.5C3 5.6716 3.6716 5 4.5 5ZM14.5 9L19.5 9C20.3284 9 21 9.6716 21 10.5L21 17.5C21 18.3284 20.3284 19 19.5 19L14.5 19C13.6716 19 13 18.3284 13 17.5L13 10.5C13 9.6716 13.6716 9 14.5 9Z");
  stroke: none;
}

</style>
