<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="fqwutob_o"/><path class="kj2waq_ni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-list-plus-sharp-fill" /></template>
<style>
.fqwutob_o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 11C22 11.5523 21.5523 12 21 12L12 12L12 21C12 21.5523 11.5523 22 11 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM9 8C9 7.4477 8.5523 7 8 7C7.4477 7 7 7.4477 7 8C7 8.5523 7.4477 9 8 9C8.5523 9 9 8.5523 9 8ZM9 12C9 11.4477 8.5523 11 8 11C7.4477 11 7 11.4477 7 12C7 12.5523 7.4477 13 8 13C8.5523 13 9 12.5523 9 12ZM9 16C9 15.4477 8.5523 15 8 15C7.4477 15 7 15.4477 7 16C7 16.5523 7.4477 17 8 17C8.5523 17 9 16.5523 9 16ZM11 7L11 9L17 9L17 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kj2waq_ni {
  d: path("M18 14L18 22M14 18L22 18");
}

</style>
