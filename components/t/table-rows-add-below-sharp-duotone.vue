<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v7v5jwbly"/><path class="slz5zy4do"/><path class="e6hc38brp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-add-below-sharp-duotone" /></template>
<style>
.e6hc38brp {
  d: path("M12 15L12 23M8 19L16 19");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.slz5zy4do {
  fill: currentColor;
  d: path("M2 12L22 12L22 2C22 1.4477 21.5523 1 21 1L3 1C2.4477 1 2 1.4477 2 2L2 12Z");
  stroke: none;
}

.v7v5jwbly {
  stroke-opacity: 0.4;
  d: path("M6 20L3 20L3 11M21 11L21 20L18 20");
}

</style>
