<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m54ltwzwe"/><path class="a3imwbbgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pause-sharp-two-tone" /></template>
<style>
.a3imwbbgx {
  d: path("M5 4L9 4L9 20L5 20L5 4ZM15 4L19 4L19 20L15 20L15 4Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m54ltwzwe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3L9 3C9.5523 3 10 3.4477 10 4L10 20C10 20.5523 9.5523 21 9 21L5 21C4.4477 21 4 20.5523 4 20L4 4C4 3.4477 4.4477 3 5 3ZM15 3L19 3C19.5523 3 20 3.4477 20 4L20 20C20 20.5523 19.5523 21 19 21L15 21C14.4477 21 14 20.5523 14 20L14 4C14 3.4477 14.4477 3 15 3Z");
  stroke: none;
}

</style>
