<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r0v1zm2cl"/><path class="wbhfocm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r0v1zm2cl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 16C23 16.5523 22.5523 17 22 17L2 17C1.4477 17 1 16.5523 1 16L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

.wbhfocm-k {
  d: path("M2 4L22 4L22 16L2 16L2 4ZM12 16L12 20M7 20L17 20");
}

</style>
