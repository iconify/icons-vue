<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wayxywj4x"/><path class="ew_kbi8qu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vesica" /></template>
<style>
.ew_kbi8qu {
  d: path("M12 6.8a6 6 0 0 1 0 10.4a6 6 0 0 1 0-10.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wayxywj4x {
  d: path("M9 6a6 6 0 1 1 0 12A6 6 0 1 1 9 6m6 0a6 6 0 1 1 0 12a6 6 0 1 1 0-12");
}

</style>
