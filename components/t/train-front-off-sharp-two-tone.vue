<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="hzssqcrwn"/><path class="gnm4lpbrb"/><path class="jguyt6bee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-off-sharp-two-tone" /></template>
<style>
.gnm4lpbrb {
  d: path("M18 18L4 18L4 4M4 9L9 9M4 5L1 5M7 18L4.7236 22.5528M17 18L19.2764 22.5528M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hzssqcrwn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 6L21 15.3432L21 17.3431L4.6569 1L20 1C20.5523 1 21.0001 1.4478 21 2.0001L21 4L23 4L23 6L21 6ZM16.1715 19L4 19C3.4477 19 3 18.5523 3 18L3 3L19 19.0001L16.1715 19Z");
  stroke: none;
}

.jguyt6bee {
  fill: currentColor;
  d: path("M10 13.5C10 14.3284 9.3284 15 8.5 15C7.6716 15 7 14.3284 7 13.5C7 12.6716 7.6716 12 8.5 12C9.3284 12 10 12.6716 10 13.5Z");
  stroke: none;
}

</style>
