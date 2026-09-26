<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fbs5khb6z"/><path class="j3akw_70p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-sharp" /></template>
<style>
.fbs5khb6z {
  d: path("M4 2L20 2L20 18L4 18L4 2ZM4 9L20 9M4 5L1 5M20 5L23 5M7 18L4.7236 22.5528M17 18L19.2764 22.5528");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j3akw_70p {
  fill: currentColor;
  d: path("M10 13.5C10 14.3284 9.3284 15 8.5 15C7.6716 15 7 14.3284 7 13.5C7 12.6716 7.6716 12 8.5 12C9.3284 12 10 12.6716 10 13.5ZM17 13.5C17 14.3284 16.3284 15 15.5 15C14.6716 15 14 14.3284 14 13.5C14 12.6716 14.6716 12 15.5 12C16.3284 12 17 12.6716 17 13.5Z");
  stroke: none;
}

</style>
