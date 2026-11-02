<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ykg0ngr9e"/><path class="m6qrz3-sl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-sparkle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m6qrz3-sl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7V5a2 2 0 0 1 2-2h2m10 0h2a2 2 0 0 1 2 2v2m0 10v2a2 2 0 0 1-2 2h-2M7 21H5a2 2 0 0 1-2-2v-2m9-10c0 3 2 5 5 5c-3 0-5 2-5 5c0-3-2-5-5-5c3 0 5-2 5-5");
}

.ykg0ngr9e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 12c-2.998.002-4.998 2.002-5 5c-.002-2.998-2.002-4.998-5-5c2.998-.002 4.998-2.002 5-5c.002 2.998 2.002 4.998 5 5");
}

</style>
