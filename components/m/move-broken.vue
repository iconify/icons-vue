<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mrobosv7g"/><path class="v-y89qb7a"/><path class="ij7wzu9ga"/><path class="ohlnn7bxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-broken" /></template>
<style>
.ij7wzu9ga {
  stroke-linejoin: round;
  d: path("M18.9467 12L22 12M19 15L22 12L19 9");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mrobosv7g {
  stroke-linejoin: round;
  d: path("M5 9L2 12L5 15M2 12L9 12");
}

.ohlnn7bxo {
  stroke-linejoin: round;
  d: path("M9.00049 5L12.0005 2L15.0005 5M12.0005 2L12.0005 9M15.0005 19L12.0005 22L9.00049 19M12.0005 22L12.0005 15");
}

.v-y89qb7a {
  d: path("M15 12L15.8934 12");
}

</style>
