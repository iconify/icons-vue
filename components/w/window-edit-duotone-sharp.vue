<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vkjb21b8v"/><path class="h54613kpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-edit-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h54613kpk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8V4h18v16H3zm0 0h18M9 17v-2l4-4l2 2l-4 4Z");
}

.vkjb21b8v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 4h18v4H3Z");
}

</style>
