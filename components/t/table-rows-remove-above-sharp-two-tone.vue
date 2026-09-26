<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="palx7jrpt"/><path class="omq-_cbgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-remove-above-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.omq-_cbgb {
  d: path("M6 4L3 4L3 22L21 22L21 4L18 4M3 13L21 13M8.7071 1.7071L15.2929 8.2929M15.2929 1.7071L8.7071 8.2929");
}

.palx7jrpt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13L21 13L21 22L3 22L3 13Z");
  stroke: none;
}

</style>
