<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="o_ly6ursf"/><path class="li_sncb5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parking-brake-light" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.li_sncb5w {
  d: path("M10.25 15.75v-7.5h2.25a2.1 2.1 0 0 1 0 4.25h-2.25m-6-6a12 12 0 0 0 0 11m15.5-11a12 12 0 0 1 0 11");
}

.o_ly6ursf {
  cx: 12px;
  cy: 12px;
  r: 6.75px;
}

</style>
