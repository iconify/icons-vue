<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wdmrbsula"/><path class="go38fkbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:solar-panel-sharp-two-tone" /></template>
<style>
.go38fkbbq {
  d: path("M6 3L18 3L22 15L2 15ZM10 3L8.6667 15M14 3L15.3333 15M4 9L20 9M12 15L12 21M7 21L17 21");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wdmrbsula {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.0513 2.6838C5.1874 2.2754 5.5696 2 6 2L18 2C18.4304 2 18.8126 2.2754 18.9487 2.6838L22.9487 14.6838C22.9827 14.7857 23 14.8925 23 15C23 15.5523 22.5523 16 22 16L2 16C1.4477 16 1 15.5523 1 15C1 14.8925 1.0173 14.7857 1.0513 14.6838Z");
  stroke: none;
}

</style>
