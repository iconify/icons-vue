<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u7solq27a"/><path class="b6-iefqln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-point-minus-sharp-two-tone" /></template>
<style>
.b6-iefqln {
  d: path("M9 9L13 9L13 13L9 13ZM2 20L2 19C2 15 5 11 9 11M13 11C17 11 22 9 22 5L22 4M15 19L23 19");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u7solq27a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 8L13 8C13.5523 8 14 8.4477 14 9L14 13C14 13.5523 13.5523 14 13 14L9 14C8.4477 14 8 13.5523 8 13L8 9C8 8.4477 8.4477 8 9 8Z");
  stroke: none;
}

</style>
