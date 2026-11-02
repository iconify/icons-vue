<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gxgmepw_c"/><path class="a8a0frbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swatches-duotone-sharp" /></template>
<style>
.a8a0frbjc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V3h8v14a4 4 0 1 1-8 0m4 0h.01M11 9l4-4l5 5L9 21m7-7h5v7H7");
}

.ft5dv1b6b {
  fill: none;
}

.gxgmepw_c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v14a5 5 0 0 1-10 0Z");
}

</style>
