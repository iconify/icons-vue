<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nnj9csb9a"/><path class="n_53gi21w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:queue-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n_53gi21w {
  d: path("M2 4L22 4L22 12L2 12L2 4ZM1 16L23 16M1 20L18 20");
}

.nnj9csb9a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 12C23 12.5523 22.5523 13 22 13L2 13C1.4477 13 1 12.5523 1 12L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

</style>
