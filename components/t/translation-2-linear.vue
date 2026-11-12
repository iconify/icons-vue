<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ehz7_oblv"/><path class="qds604bnv"/><circle class="h_tsn8bxt"/><path class="rww_ujanv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:translation-2-linear" /></template>
<style>
.ehz7_oblv {
  d: path("M16.2426 16.2426C17.3284 15.1569 18 13.6569 18 12C18 8.68629 15.3137 6 12 6C8.68629 6 6 8.68629 6 12C6 13.6569 6.67157 15.1569 7.75736 16.2426");
}

.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qds604bnv {
  d: path("M4.92893 19.0711C3.11929 17.2614 2 14.7614 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 14.7614 20.8807 17.2614 19.0711 19.0711");
}

.rww_ujanv {
  d: path("M12 22C9.04784 22 7.57176 22 7.14161 21.2301C7.10463 21.1639 7.07344 21.0952 7.04832 21.0245C6.75612 20.2025 7.79987 19.2497 9.88736 17.3441C10.8467 16.4683 11.3264 16.0304 11.9187 16.002C11.9729 15.9993 12.0271 15.9993 12.0813 16.002C12.6736 16.0304 13.1533 16.4683 14.1126 17.3441C16.2001 19.2497 17.2439 20.2025 16.9517 21.0245C16.9266 21.0952 16.8954 21.1639 16.8584 21.2301C16.4282 22 14.9522 22 12 22Z");
}

</style>
