<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w0tvgeb3q"/><path class="fra41bbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sports-equipment-rental" /></template>
<style>
.fra41bbpn {
  d: path("M16.25 9.5c-.5-1-1.5-1.25-2.25-1.25c-1.25 0-2.25.75-2.25 2c0 2.5 4.5 1.25 4.5 3.75c0 1.25-1 1.75-2.25 1.75c-1 0-2-.5-2.25-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w0tvgeb3q {
  d: path("M9.905 4.5h6.97A2.625 2.625 0 0 1 19.5 7.125v9.75a2.625 2.625 0 0 1-2.625 2.625h-6.97a2.63 2.63 0 0 1-2.184-1.169l-3.25-4.875a2.625 2.625 0 0 1 0-2.912l3.25-4.875A2.63 2.63 0 0 1 9.905 4.5M8.25 12h.01M14 7.25v9.5");
}

</style>
