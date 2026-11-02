<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vwjy5ebuh"/><path class="xfiflm3ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.vwjy5ebuh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 20a1.002 1.002 0 0 1-1.707.707L9.586 17H6a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3.586l3.707-3.707A1 1 0 0 1 15 4Z");
}

.xfiflm3ht {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8H6v8h4l4 4v-6m0-6V4l-2 2M2 2l20 20");
}

</style>
