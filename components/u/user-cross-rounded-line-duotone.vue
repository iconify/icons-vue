<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l5s0pfbji"/><circle class="dtl23o_xq"/><path class="gx0h1ccej"/><path class="rdnf-acrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-cross-rounded-line-duotone" /></template>
<style>
.dtl23o_xq {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

.gx0h1ccej {
  stroke-linejoin: round;
  d: path("M15.666 16.6667L16.9995 18.0002M16.9995 18.0002L18.3327 19.3333M16.9995 18.0002L18.333 16.6667M16.9995 18.0002L15.6663 19.3333");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5s0pfbji {
  d: path("M16.683 14.0124C15.4431 13.3838 13.8093 13.0019 12.019 13.0019C8.14253 13.0019 5 14.7924 5 17.001C5 19.2096 8.14253 21 12.019 21C12.7637 21 13.4813 20.9339 14.1548 20.8115");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rdnf-acrq {
  d: path("M21 18C21 20.2091 19.2091 22 17 22C15.8869 22 14.8799 21.5453 14.1548 20.8115C13.4408 20.089 13 19.096 13 18C13 15.8976 14.6221 14.174 16.683 14.0124C16.7876 14.0042 16.8933 14 17 14C19.2091 14 21 15.7909 21 18Z");
}

</style>
