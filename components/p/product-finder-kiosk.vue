<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r57dq0ble"/><path class="e_m-orbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:product-finder-kiosk" /></template>
<style>
.e_m-orbfw {
  d: path("M12 12c-2-2-3-3.5-3-4.75a3 3 0 0 1 6 0C15 8.5 14 10 12 12m0-4.75h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r57dq0ble {
  d: path("M7.363 2.5h9.274a2.625 2.625 0 0 1 2.615 2.852l-.544 6.25A2.625 2.625 0 0 1 16.093 14H7.907a2.625 2.625 0 0 1-2.615-2.398l-.544-6.25A2.625 2.625 0 0 1 7.363 2.5M11.5 14h1a1.5 1.5 0 0 1 1.5 1.5V18a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 18v-2.5a1.5 1.5 0 0 1 1.5-1.5m-5 7.5h11");
}

</style>
