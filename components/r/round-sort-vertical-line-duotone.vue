<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="fa7lsebpo"/><path class="qsgur_bab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-sort-vertical-line-duotone" /></template>
<style>
.doy9q4b5f {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.fa7lsebpo {
  stroke-linejoin: round;
  d: path("M9.5 8L9.5 16M12 13.25L9.5 16L7 13.25");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qsgur_bab {
  stroke-linejoin: round;
  d: path("M14.5 16L14.5 8M17 10.75L14.5 8L12 10.75");
}

</style>
