<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ay3lmyx_t"/><path class="sp921pbky"/><path class="uz3lsgu5b"/><path class="s3ky5ibnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:upscale-duotone-bold" /></template>
<style>
.ay3lmyx_t {
  fill: currentColor;
  d: path("M2 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s3ky5ibnb {
  d: path("M15 4h5v5");
}

.sp921pbky {
  d: path("M2 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.uz3lsgu5b {
  d: path("m14 10 6 -6");
}

</style>
