<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kd07owbii"/><path class="cxnrrk41g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-headset-duotone-sharp" /></template>
<style>
.cxnrrk41g {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10a4 4 0 1 0 8 0a4 4 0 0 0-8 0M4 21c0-2.21 3.582-4 8-4s8 1.79 8 4M5 10a7 7 0 0 1 14 0M5 10H3v4h2zm14 0h2v4h-2zm1 4v1h-2");
}

.ft5dv1b6b {
  fill: none;
}

.kd07owbii {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 10a4 4 0 1 1 8 0a4 4 0 0 1-8 0M4 21c0-2.209 3.582-4 8-4s8 1.791 8 4Z");
}

</style>
