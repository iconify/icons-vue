<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m-rom16pb"/><path class="a6lrqzbxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-search-sharp-two-tone" /></template>
<style>
.a6lrqzbxm {
  d: path("M14 11C14 12.6569 12.6569 14 11 14C9.3431 14 8 12.6569 8 11C8 9.3431 9.3431 8 11 8C12.6569 8 14 9.3431 14 11ZM13 13L16.2929 16.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m-rom16pb {
  stroke-opacity: 0.4;
  d: path("M3 9L3 3L9 3M15 3L21 3L21 9M21 15L21 21L15 21M9 21L3 21L3 15");
}

</style>
