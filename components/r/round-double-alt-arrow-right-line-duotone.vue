<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="a5yqgt9oz"/><path class="o_vsnhzlf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-right-line-duotone" /></template>
<style>
.a5yqgt9oz {
  stroke-linejoin: round;
  d: path("M8.5 9L11.5 12L8.5 15");
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

.o_vsnhzlf {
  stroke-linejoin: round;
  d: path("M12.5 9L15.5 12L12.5 15");
}

</style>
