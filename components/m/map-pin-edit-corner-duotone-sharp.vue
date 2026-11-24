<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d6zzytpmw"/><path class="tpnjamt1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-edit-corner-duotone-sharp" /></template>
<style>
.d6zzytpmw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.982 9.5a7.502 7.502 0 0 0-7.405 8.572L10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5M14 21v-3l4-4l3 3l-4 4Z");
}

.ft5dv1b6b {
  fill: none;
}

.tpnjamt1w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5M8 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 12v-3l4-4l3 3l-4 4Z");
}

</style>
