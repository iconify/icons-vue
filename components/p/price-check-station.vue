<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kq77qcc5x"/><path class="rla7lmb_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-check-station" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kq77qcc5x {
  d: path("M12 2.5v2m-5.875 0h11.75A2.625 2.625 0 0 1 20.5 7.125v4.75a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 11.875v-4.75A2.625 2.625 0 0 1 6.125 4.5");
}

.rla7lmb_g {
  d: path("M10.203 6.5H15A1.5 1.5 0 0 1 16.5 8v3a1.5 1.5 0 0 1-1.5 1.5h-4.797a1.5 1.5 0 0 1-1.153-.54l-1.25-1.5a1.5 1.5 0 0 1 0-1.92l1.25-1.5a1.5 1.5 0 0 1 1.153-.54m-.453 3h.01m4.99 7.75v4.25M17 17.25v4.25m2.25-4.25v4.25m2.25-4.25v4.25");
}

</style>
