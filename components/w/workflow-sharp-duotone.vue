<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="giuwft-_j"/><path class="rd6iclxvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:workflow-sharp-duotone" /></template>
<style>
.giuwft-_j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M3 3L11 3C11.5523 3 12 3.4477 12 4L12 10C12 10.5523 11.5523 11 11 11L3 11C2.4477 11 2 10.5523 2 10L2 4C2 3.4477 2.4477 3 3 3ZM13 13L21 13C21.5523 13 22 13.4477 22 14L22 20C22 20.5523 21.5523 21 21 21L13 21C12.4477 21 12 20.5523 12 20L12 14C12 13.4477 12.4477 13 13 13Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rd6iclxvz {
  d: path("M7 10L7 17L13 17");
}

</style>
