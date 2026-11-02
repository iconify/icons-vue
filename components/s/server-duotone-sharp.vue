<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vnmktlbce"/><path class="kvwxddsao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kvwxddsao {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v6H3Zm0 10h18v6H3Zm4-7h.01M7 17h.01");
}

.vnmktlbce {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 4v6H3V4Zm0 10v6H3v-6Z");
}

</style>
