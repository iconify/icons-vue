<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x45v0gbbp"/><path class="xyx153nsw"/><path class="i4b36nbqn"/><path class="h_w57hb4v"/><path class="acqm3gzcu"/><path class="e88v2dymu"/><path class="ucteibp9l"/><path class="ulc8o-bhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-line-duotone" /></template>
<style>
.acqm3gzcu {
  d: path("M12.0002 1.99976L12.0002 8.99975");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.e88v2dymu {
  stroke-linejoin: round;
  d: path("M15.0002 4.99976L12.0002 1.99976L9.00024 4.99976");
}

.h_w57hb4v {
  stroke-linejoin: round;
  d: path("M19.0005 15L22.0005 12L19.0005 9");
}

.i4b36nbqn {
  d: path("M22.0005 12L15.0005 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ucteibp9l {
  d: path("M12.0002 22.0002L12.0002 15.0002");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ulc8o-bhl {
  stroke-linejoin: round;
  d: path("M9.00024 19.0002L12.0002 22.0002L15.0002 19.0002");
}

.x45v0gbbp {
  d: path("M2 12L9 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xyx153nsw {
  stroke-linejoin: round;
  d: path("M5 9L2 12L5 15");
}

</style>
