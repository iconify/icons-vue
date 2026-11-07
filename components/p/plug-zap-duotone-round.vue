<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g_fx8tvqi"/><path class="qjredeevn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-zap-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g_fx8tvqi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 6a5 5 0 0 1 5 5v2a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-2a5 5 0 0 1 5-5Z");
}

.qjredeevn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7h1a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-2a4 4 0 0 1 4-4zM6 3v4m4-4v4M8 17v4M20 7l-3 5h4l-3 5");
}

</style>
