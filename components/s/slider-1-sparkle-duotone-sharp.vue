<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hd39rgtjx"/><path class="bon5vccnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-1-sparkle-duotone-sharp" /></template>
<style>
.bon5vccnt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M3 6h2m4 0h2M3 18h8m4 0h6M18 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.ft5dv1b6b {
  fill: none;
}

.hd39rgtjx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14-3c.002 1.005 1.995 2.998 3 3c-1.005.002-2.998 1.995-3 3c-.002-1.005-1.995-2.998-3-3c1.005-.002 2.998-1.995 3-3m-8 15a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
