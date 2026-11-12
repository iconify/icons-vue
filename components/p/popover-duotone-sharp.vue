<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tn2qjhb0v"/><path class="m4cm_jb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:popover-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m4cm_jb5t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h6l3-4l3 4h6v14H3zm4 5h10M7 16h6");
}

.tn2qjhb0v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m9 7l3-4l3 4h6v14H3V7Z");
}

</style>
