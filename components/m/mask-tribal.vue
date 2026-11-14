<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ulzse2bkv"/><path class="mbdk-bc-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mask-tribal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbdk-bc-b {
  d: path("M9.679 9h.142a.654.654 0 0 1 .554 1a.737.737 0 0 1-1.25 0a.654.654 0 0 1 .554-1m4.5 0h.142a.654.654 0 0 1 .554 1a.737.737 0 0 1-1.25 0a.654.654 0 0 1 .554-1M12 11v3.5m-2 3h4");
}

.ulzse2bkv {
  d: path("M6 12a6 9.5 0 1 0 12 0a6 9.5 0 1 0-12 0");
}

</style>
