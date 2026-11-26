<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xvht8mb3n"/><path class="wkqp4yi6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pitcher-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wkqp4yi6g {
  d: path("M2.0005 4L18 4L16 20L8 20L6.5 8ZM17.5 8L18 8C20.2091 8 22 9.7909 22 12C22 14.2091 20.2091 16 18 16L16.5 16M7 12L17 12");
}

.xvht8mb3n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.9923 12.124L16.9923 20.124C16.9297 20.6245 16.5043 21 16 21L8 21C7.4957 21 7.0703 20.6245 7.0077 20.124L5.5544 8.4974L1.3361 4.7474C1.1226 4.5576 1.0005 4.2856 1.0005 4C1.0005 3.4477 1.4482 3 2.0005 3L18 3C18.5523 3 19 3.4477 19 4C19 4.0415 18.9974 4.0829 18.9923 4.124Z");
  stroke: none;
}

</style>
