<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y4sc2bbph"/><circle class="m_f5uw_8g"/><path class="aewalzb3w"/><path class="mrov9tb8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-hospital-linear" /></template>
<style>
.aewalzb3w {
  d: path("M10.5 10H13.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_f5uw_8g {
  cx: 12px;
  cy: 10px;
  r: 4px;
}

.mrov9tb8p {
  d: path("M12 11.5L12 8.5");
}

.y4sc2bbph {
  d: path("M13.4629 21.6744C12.5343 22.1085 11.4657 22.1085 10.5371 21.6744C6.55332 19.8124 4 14.6055 4 10.1433C4 5.64588 7.58172 2 12 2C16.4183 2 20 5.64588 20 10.1433C20 14.6055 17.4467 19.8124 13.4629 21.6744Z");
}

</style>
