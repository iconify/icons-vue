<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m24tlfb8a"/><path class="dcr-jtrug"/><path class="uisun-o6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:traffic-light-red-amber" /></template>
<style>
.dcr-jtrug {
  fill: currentColor;
  d: path("M10.5 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m24tlfb8a {
  d: path("M12 2za4.25 4.25 0 0 1 4.25 4.25v11.5A4.25 4.25 0 0 1 12 22a4.25 4.25 0 0 1-4.25-4.25V6.25A4.25 4.25 0 0 1 12 2");
}

.uisun-o6j {
  d: path("M10.5 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
