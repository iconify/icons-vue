<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pkw7z1bdm"/><path clip-rule="evenodd" class="soykp47fv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-exclude-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pkw7z1bdm {
  stroke-opacity: 0.4;
  d: path("M12 9L9 9L9 12M15 12L15 15L12 15");
}

.soykp47fv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2L15 2C15.5523 2 16 2.4477 16 3L16 8L21 8C21.5523 8 22 8.4477 22 9L22 21C22 21.5523 21.5523 22 21 22L9 22C8.4477 22 8 21.5523 8 21L8 16L3 16C2.4477 16 2 15.5523 2 15L2 3C2 2.4477 2.4477 2 3 2ZM12 10L12 8L9 8C8.4477 8 8 8.4477 8 9L8 12L10 12L10 10ZM16 12L14 12L14 14L12 14L12 16L15 16C15.5523 16 16 15.5523 16 15Z");
  stroke: none;
}

</style>
