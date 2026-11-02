<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="web-obyff"/><path class="ghr-fk6dg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ghr-fk6dg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m0 10a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3M7 7h.01M7 17h.01");
}

.web-obyff {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 4h12a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6m0 10h12a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6");
}

</style>
