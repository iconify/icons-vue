<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zd0trsbfq"/><path class="r6843cb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-corner-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r6843cb3g {
  d: path("M10 5L14 5L14 9L10 9ZM10 8L1.8126 19.4172M14 8L22.1874 19.4172");
}

.zd0trsbfq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4L14 4C14.5523 4 15 4.4477 15 5L15 9C15 9.5523 14.5523 10 14 10L10 10C9.4477 10 9 9.5523 9 9L9 5C9 4.4477 9.4477 4 10 4Z");
  stroke: none;
}

</style>
