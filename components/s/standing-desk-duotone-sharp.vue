<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qz938abwq"/><path class="g9p7l4buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:standing-desk-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g9p7l4buq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20v-4h18v4M11 4h10v8H11Zm5 8v4M3 6l2-2l2 2m-4 4l2 2l2-2");
}

.qz938abwq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4h10v8H11Z");
}

</style>
