<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="g8opcxb4u"/><path class="sfotcmble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-cells-split-sharp-fill" /></template>
<style>
.g8opcxb4u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 9L21 9L21 15L3 15L3 9ZM6.5 10L6.5 14L8.5 14L8.5 10ZM11 10L11 14L13 14L13 10ZM15.5 10L15.5 14L17.5 14L17.5 10Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sfotcmble {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM12 3L12 9M12 15L12 21M3 9L21 9M3 15L21 15");
}

</style>
