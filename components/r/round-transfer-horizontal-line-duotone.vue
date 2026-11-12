<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="cavrtqb0h"/><path class="yvp5mpkiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-transfer-horizontal-line-duotone" /></template>
<style>
.cavrtqb0h {
  stroke-linejoin: round;
  d: path("M17 10L7 10L10.4375 7");
}

.doy9q4b5f {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yvp5mpkiq {
  stroke-linejoin: round;
  d: path("M7 14L17 14L13.5625 17");
}

</style>
