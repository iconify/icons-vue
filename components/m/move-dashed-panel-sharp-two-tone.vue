<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sw6e1rbyi"/><path class="v1k8bcdur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:move-dashed-panel-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sw6e1rbyi {
  stroke-opacity: 0.4;
  d: path("M3 7L3 3L7 3M9 3L14 3M20 8L20 3L16 3M8 20L3 20L3 16M3 9L3 14");
}

.v1k8bcdur {
  d: path("M9 15L21 15M15 9L15 21M10.7929 13.2071L9 15L10.7929 16.7929M19.2071 13.2071L21 15L19.2071 16.7929M13.2071 10.7929L15 9L16.7929 10.7929M13.2071 19.2071L15 21L16.7929 19.2071");
}

</style>
