<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fs-evbclu"/><path class="jgn5bbb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:users-sharp-duotone" /></template>
<style>
.fs-evbclu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 13L10 13C13.7279 13 17 16.2721 17 20L17 21C17 21.5523 16.5523 22 16 22L2 22C1.4477 22 1 21.5523 1 21L1 20C1 16.2721 4.2721 13 8 13ZM9 3C11.0711 3 13 4.9289 13 7C13 9.0711 11.0711 11 9 11C6.9289 11 5 9.0711 5 7C5 4.9289 6.9289 3 9 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jgn5bbb2d {
  d: path("M15 4L16 4C17.6569 4 19 5.3431 19 7C19 8.6569 17.6569 10 16 10L15 10M17.4121 14.0823L18.3333 14.4713C20.554 15.409 22 17.589 22 20C22 20.5523 21.5523 21 21 21L20 21");
}

</style>
