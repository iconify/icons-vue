<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d3y2sibbn"/><path class="jbv-3xo9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-duotone" /></template>
<style>
.d3y2sibbn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m0 10h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3");
}

.ft5dv1b6b {
  fill: none;
}

.jbv-3xo9y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10H5a2 2 0 0 1-2-2V6c0-.811.306-1.686 1-2m6 0h9a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-3m4 10c-.251.114-.707 0-1 0H5a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h9m-7 3h.01M2 2l20 20");
}

</style>
