<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c-fn48bus"/><path class="a-22vyg5o"/><path clip-rule="evenodd" class="xe6tfdcfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-notes-sharp-duotone" /></template>
<style>
.a-22vyg5o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 14L20.5858 14L16 9.4142Z");
  stroke: none;
}

.c-fn48bus {
  stroke-opacity: 0.4;
  d: path("M16 5L16.0001 2L2 2L2 16.0001L5 16");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xe6tfdcfq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 7L16 7C16.2652 7 16.5196 7.1054 16.7071 7.2929L22.7071 13.2929C22.8946 13.4804 23 13.7348 23 14L23 22C23 22.5523 22.5523 23 22 23L8 23C7.4477 23 7 22.5523 7 22L7 8C7 7.4477 7.4477 7 8 7ZM16 14L20.5858 14L16 9.4142Z");
  stroke: none;
}

</style>
