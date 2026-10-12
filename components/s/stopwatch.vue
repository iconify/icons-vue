<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="fhcsjwttb"/><path class="si7a6shde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stopwatch" /></template>
<style>
.fhcsjwttb {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.si7a6shde {
  d: path("M10 2.75h4m-2 0v3M17.5 8l1.75-1.75M12 13.5l2.75-2.75");
}

</style>
