<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="opjw_ubeb"/><path class="f32yb1bfl"/><path class="l7n3r2b0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spare-tire" /></template>
<style>
.f32yb1bfl {
  d: path("M12 8a3 3 0 1 0 0 6a3 3 0 0 0 0-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7n3r2b0z {
  d: path("M2.75 11.5v4.75a5 5 0 0 0 5 5h8.5a5 5 0 0 0 5-5V11.5");
}

.opjw_ubeb {
  cx: 12px;
  cy: 11px;
  r: 7.25px;
}

</style>
