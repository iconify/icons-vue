<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rwae0ibcz"/><path class="xkf0yzo5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-zap-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rwae0ibcz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 17V7a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

.xkf0yzo5e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h10v10H3zm3-4v4m4-4v4M8 17v4M20 7l-3 5h4l-3 5");
}

</style>
