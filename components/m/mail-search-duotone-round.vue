<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fq_69_1li"/><path class="iv0ulmjvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-duotone-round" /></template>
<style>
.fq_69_1li {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 15a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h3a.998.998 0 0 1 .986 1.164a5 5 0 0 0 .174 2.387a5.08 5.08 0 0 0 6.194 3.348a1 1 0 0 1 .973.257l1.259 1.258A2 2 0 0 0 21 13a1 1 0 0 1 1 1Z");
}

.ft5dv1b6b {
  fill: none;
}

.iv0ulmjvb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14v1a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h3M4 7l3 3c.64.64 1.72 1 3 1h2m2-7a2.828 2.828 0 1 1 4 4a2.828 2.828 0 0 1-4-4m4 4l3 3");
}

</style>
