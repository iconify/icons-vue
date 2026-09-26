<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nz4nte95p"/><path class="jgv618mbj"/><path class="zvepp4dfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-close-dashed-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jgv618mbj {
  d: path("M3 17L3 21L7 21M17 21L21 21L21 17M3 12L3 15M21 12L21 15M9.5 21L14.5 21");
}

.nz4nte95p {
  fill: currentColor;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 9C22 9.5523 21.5523 10 21 10L3 10C2.4477 10 2 9.5523 2 9L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

.zvepp4dfu {
  d: path("M8.7071 16.2929L12 13L15.2929 16.2929");
}

</style>
