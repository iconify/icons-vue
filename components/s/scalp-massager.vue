<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qceyknt9s"/><path class="anr41ub1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scalp-massager" /></template>
<style>
.anr41ub1a {
  d: path("M10 15.25v4.25a2 2 0 0 0 4 0v-4.25M12 6h.01M9 9.5h.01m5.99 0h.01m-3.01 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qceyknt9s {
  d: path("M5 9a7 6.5 0 1 0 14 0A7 6.5 0 1 0 5 9");
}

</style>
