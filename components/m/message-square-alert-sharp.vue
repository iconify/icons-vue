<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k0cuwpsgz"/><path clip-rule="evenodd" class="gd25r_74b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-alert-sharp" /></template>
<style>
.gd25r_74b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 13C13 13.5523 12.5523 14 12 14C11.4477 14 11 13.5523 11 13C11 12.4477 11.4477 12 12 12C12.5523 12 13 12.4477 13 13Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k0cuwpsgz {
  d: path("M3 3L21 3L21 17L7 17L3 21L3 3ZM12 6L12 7L12 9L12 10");
}

</style>
