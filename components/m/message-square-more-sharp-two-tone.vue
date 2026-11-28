<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f_aom9iip"/><path class="c-jrmt4kx"/><path clip-rule="evenodd" class="qwar3iq0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-more-sharp-two-tone" /></template>
<style>
.c-jrmt4kx {
  d: path("M3 3H21V17H7L3 21V3Z");
}

.f_aom9iip {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2H21C21.552 2 22 2.448 22 3V17C22 17.552 21.552 18 21 18H7.414L3.707 21.707C3.52 21.895 3.265 22 3 22C2.448 22 2 21.552 2 21V3C2 2.448 2.448 2 3 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qwar3iq0x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.333 8.667C8.07 8.667 8.667 9.264 8.667 10C8.667 10.736 8.07 11.333 7.333 11.333C6.597 11.333 6 10.736 6 10C6 9.264 6.597 8.667 7.333 8.667ZM12 8.667C12.736 8.667 13.333 9.264 13.333 10C13.333 10.736 12.736 11.333 12 11.333C11.264 11.333 10.667 10.736 10.667 10C10.667 9.264 11.264 8.667 12 8.667ZM16.667 8.667C17.403 8.667 18 9.264 18 10C18 10.736 17.403 11.333 16.667 11.333C15.93 11.333 15.333 10.736 15.333 10C15.333 9.264 15.93 8.667 16.667 8.667Z");
  stroke: none;
}

</style>
