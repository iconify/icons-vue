<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="agkvw0bhq"/><path class="h6j440bgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paintbrush-sharp-two-tone" /></template>
<style>
.agkvw0bhq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1L18 1C18.5523 1 19 1.4477 19 2L19 11L19 11C19.5523 11 20 11.4477 20 12L20 16C20 16.5523 19.5523 17 19 17L15.0198 17L15.9806 21.8039C15.9935 21.8685 16 21.9341 16 22C16 22.5523 15.5523 23 15 23L9 23C8.4477 23 8 22.5523 8 22C8 21.9341 8.0065 21.8685 8.0194 21.8039L8.5194 19.3039L8.9802 17L5 17C4.4477 17 4 16.5523 4 16L4 12C4 11.4477 4.4477 11 5 11L5 11L5 2C5 1.4477 5.4477 1 6 1L12 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h6j440bgc {
  d: path("M12 2L18 2L18 12L19 12L19 16L13.8 16L15 22L9 22L9.5 19.5L10.2 16L5 16L5 12L6 12L6 2ZM6 12L18 12M10 2L10 7M14 2L14 9");
}

</style>
