<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m0z_pzvrc"/><path class="ue2_f7zks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-plus-corner-duocolor-sharp" /></template>
<style>
.m0z_pzvrc {
  stroke-opacity: 0.4;
  d: path("M13 17h8m-4-4v8");
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
