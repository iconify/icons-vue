<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v8hgvi38z"/><path clip-rule="evenodd" class="i_l1wbidz"/><path class="w3iztdbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vault-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i_l1wbidz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 6L17 6C17.5523 6 18 6.4477 18 7L18 17C18 17.5523 17.5523 18 17 18L7 18C6.4477 18 6 17.5523 6 17L6 7C6 6.4477 6.4477 6 7 6ZM14 10L12 10L12 14L14 14L14 10Z");
  stroke: none;
}

.v8hgvi38z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

.w3iztdbfb {
  d: path("M4 10L7 10M4 14L7 14");
}

</style>
