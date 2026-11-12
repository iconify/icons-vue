<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fhclqv_fm"/><path class="ue2_f7zks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-settings-corner-duocolor-sharp" /></template>
<style>
.fhclqv_fm {
  stroke-opacity: 0.4;
  d: path("M14 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3-3v-1m2.598 2.5l.866-.5m-.866 3.5l.866.5M17 20v1m-2.598-2.5l-.866.5m.866-3.5l-.866-.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ue2_f7zks {
  d: path("M3 8V4h18v4M8 20H3V8m0 0h18");
}

</style>
