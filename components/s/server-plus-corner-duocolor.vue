<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m0z_pzvrc"/><path class="kc00_sgya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-plus-corner-duocolor" /></template>
<style>
.kc00_sgya {
  d: path("M3 6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm0 8h6m0 6H5a2 2 0 0 1-2-2v-4m4-7h.01M7 17h.01");
}

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

</style>
