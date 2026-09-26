<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yd9dbjjnf"/><path class="ooa_3hbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-remove-below-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ooa_3hbcq {
  d: path("M6 20L3 20L3 2L21 2L21 20L18 20M3 11L21 11M8.7071 15.7071L15.2929 22.2929M15.2929 15.7071L8.7071 22.2929");
}

.yd9dbjjnf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11L21 11L21 2L3 2L3 11Z");
  stroke: none;
}

</style>
