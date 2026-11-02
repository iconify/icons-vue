<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n9aki8bjc"/><path class="klkhsmlzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-sparkle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.klkhsmlzp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5v7a2 2 0 1 0 4 0V5a2 2 0 1 0-4 0m2 13v3m-6-9a6 6 0 1 0 12 0m3-9c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.n9aki8bjc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 5a3 3 0 1 1 6 0v7a3 3 0 1 1-6 0Zm12-2c.002 1.005 1.995 2.998 3 3c-1.005.002-2.998 1.995-3 3c-.002-1.005-1.995-2.998-3-3c1.005-.002 2.998-1.995 3-3");
}

</style>
