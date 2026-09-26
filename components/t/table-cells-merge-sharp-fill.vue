<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ur1qnibrv"/><path class="sfotcmble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-cells-merge-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sfotcmble {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM12 3L12 9M12 15L12 21M3 9L21 9M3 15L21 15");
}

.ur1qnibrv {
  fill: currentColor;
  d: path("M3 9L21 9L21 15L3 15L3 9Z");
  stroke: none;
}

</style>
