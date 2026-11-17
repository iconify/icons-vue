<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dv_v2cpwr"/><path class="p-3aw-slw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-duotone" /></template>
<style>
.dv_v2cpwr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 12c2 2 2 3 1 4s-2 1-4-1l-2-2l-5.492.915a1 1 0 0 1-.872-.279L5.5 13.5a.61.61 0 0 1 .066-.924L9 10L8 8H6.414a1 1 0 0 1-.707-.293L5.5 7.5a.707.707 0 0 1 0-1l3-3a.707.707 0 0 1 1 0l.207.207a1 1 0 0 1 .293.707V6l2 1l2.576-3.434A.61.61 0 0 1 15.5 3.5l.136.136c.228.228.332.553.279.872L15 10Z");
}

.ft5dv1b6b {
  fill: none;
}

.p-3aw-slw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 12l-2-2l.915-5.492a1 1 0 0 0-.279-.872L15.5 3.5a.613.613 0 0 0-.924.066L12 7l-2-1V4.414a1 1 0 0 0-.293-.707L9.5 3.5a.707.707 0 0 0-1 0l-3 3a.707.707 0 0 0 0 1l.207.207A1 1 0 0 0 6.414 8H8l1 2l-3.434 2.576a.613.613 0 0 0-.066.924l.136.136a1 1 0 0 0 .872.28L12 13l2 2c2 2 3 2 4 1s1-2-1-4M3 21h18");
}

</style>
