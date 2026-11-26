<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dj7bubbqk"/><path class="og-3ihbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:martini-sharp-two-tone" /></template>
<style>
.dj7bubbqk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2L22 2C22.5523 2 23 2.4477 23 3C23 3.2521 22.9048 3.4948 22.7335 3.6797L12.7335 14.4706C12.5442 14.6748 12.2784 14.7909 12 14.7909C11.7216 14.7909 11.4558 14.6748 11.2665 14.4706L1.2665 3.6797C1.0952 3.4948 1 3.2521 1 3C1 2.4477 1.4477 2 2 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.og-3ihbor {
  d: path("M2 3L22 3L12 13.7909ZM5.7078 7L18.2922 7M12 13.7909L12 21M5 21L6 21L18 21L19 21");
}

</style>
