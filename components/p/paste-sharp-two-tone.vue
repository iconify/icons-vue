<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="vx2ry1y7c"/><path class="a5uo1zb2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paste-sharp-two-tone" /></template>
<style>
.a5uo1zb2z {
  d: path("M5 4L2 4L2 21L9 21M13 4L16 4L16 8M5 2L13 2L13 7L5 7L5 2ZM18 11L12 11L12 22L22 22L22 15L18 11ZM18 11L18 15L22 15");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vx2ry1y7c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M5 1L13 1C13.5523 1 14 1.4477 14 2L14 7C14 7.5523 13.5523 8 13 8L5 8C4.4477 8 4 7.5523 4 7L4 2C4 1.4477 4.4477 1 5 1ZM18 10C18.2652 10 18.5196 10.1054 18.7071 10.2929L22.7071 14.2929C22.8946 14.4804 23 14.7348 23 15L23 22C23 22.5523 22.5523 23 22 23L12 23C11.4477 23 11 22.5523 11 22L11 11C11 10.4477 11.4477 10 12 10L18 10Z");
  stroke: none;
}

</style>
