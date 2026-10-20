<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="h72b5xbid"/><path class="m77kogrek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-play-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h72b5xbid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 2L22 2C22.5523 2 23 2.4477 23 3L23 17C23 17.5523 22.5523 18 22 18L2 18C1.4477 18 1 17.5523 1 17L1 3C1 2.4477 1.4477 2 2 2ZM10.561 6.1722C10.3954 6.06 10.2 6 10 6C9.4477 6 9 6.4477 9 7L9 13C9 13.5523 9.4477 14 10 14C10.2 14 10.3954 13.94 10.561 13.8278L14.9877 10.8278C15.2623 10.6417 15.4267 10.3317 15.4267 10C15.4267 9.6683 15.2623 9.3583 14.9877 9.1722L10.561 6.1722Z");
  stroke: none;
}

.m77kogrek {
  d: path("M12 17L12 21M7 21L17 21");
}

</style>
