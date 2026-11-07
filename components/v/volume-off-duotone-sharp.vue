<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q-pxiccwb"/><path class="xfiflm3ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q-pxiccwb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 6l2-2v4Zm2 14l-4-4H6V8h2l6 6Z");
}

.xfiflm3ht {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8H6v8h4l4 4v-6m0-6V4l-2 2M2 2l20 20");
}

</style>
