<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aadfj7byu"/><path class="dtg7nbaxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-closed" /></template>
<style>
.aadfj7byu {
  d: path("M5.625 2.5h12.75A2.625 2.625 0 0 1 21 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875V5.125A2.625 2.625 0 0 1 5.625 2.5M12 2.5v19M3 12h18");
}

.dtg7nbaxt {
  d: path("M16 14.75zA1.25 1.25 0 0 1 17.25 16v1.5A1.25 1.25 0 0 1 16 18.75a1.25 1.25 0 0 1-1.25-1.25V16A1.25 1.25 0 0 1 16 14.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
