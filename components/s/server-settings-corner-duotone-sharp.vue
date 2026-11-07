<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tsfyb9jvh"/><path class="bh1gb625g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-settings-corner-duotone-sharp" /></template>
<style>
.bh1gb625g {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v6H3Zm0 10h6m0 6H3v-6m4-7h.01M7 17h.01M14 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3-3v-1m2.598 2.5l.866-.5m-.866 3.5l.866.5M17 20v1m-2.598-2.5l-.866.5m.866-3.5l-.866-.5");
}

.ft5dv1b6b {
  fill: none;
}

.tsfyb9jvh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1ZM9 13a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1Z");
}

</style>
