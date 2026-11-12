<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="purcbkvjm"/><path class="ucmmg78pb"/><path class="h75qk2bse"/><path class="gi9zy4bja"/><path class="fbnn_3bad"/><circle class="gvyc-o7fz"/><path class="rgnmckb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-2-line-duotone" /></template>
<style>
.fbnn_3bad {
  d: path("M17 16.5V12.5V8");
}

.gi9zy4bja {
  d: path("M8 18H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gvyc-o7fz {
  cx: 14.5px;
  cy: 16.5px;
  r: 2.5px;
}

.h75qk2bse {
  d: path("M9 14H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.purcbkvjm {
  d: path("M15 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rgnmckb3y {
  d: path("M21 12C18.7909 12 17 10.2091 17 8");
}

.ucmmg78pb {
  d: path("M13 10L3 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
