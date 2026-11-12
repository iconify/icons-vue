<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="capvx_qns"/><path class="lcbsa_hbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-settings-corner-duotone" /></template>
<style>
.capvx_qns {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 9a1 1 0 0 1-1-1V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1Z");
}

.ft5dv1b6b {
  fill: none;
}

.lcbsa_hbs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8V6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2M8 20H5a2 2 0 0 1-2-2V8m0 0h18m-7 9a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3-3v-1m2.598 2.5l.866-.5m-.866 3.5l.866.5M17 20v1m-2.598-2.5l-.866.5m.866-3.5l-.866-.5");
}

</style>
