<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fi345qldm"/><path class="ift3yubeo"/><path class="zvepp4dfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-close-dashed-sharp-two-tone" /></template>
<style>
.fi345qldm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM3 3L3 9L21 9L21 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ift3yubeo {
  d: path("M3 9L3 3L21 3L21 9L3 9ZM3 17L3 21L7 21M17 21L21 21L21 17M3 12L3 15M21 12L21 15M9.5 21L14.5 21");
}

.zvepp4dfu {
  d: path("M8.7071 16.2929L12 13L15.2929 16.2929");
}

</style>
