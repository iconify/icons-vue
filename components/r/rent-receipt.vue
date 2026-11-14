<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_rqkgbls"/><path class="ti9h6i7qm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rent-receipt" /></template>
<style>
.c_rqkgbls {
  d: path("M5.5 2.5h13v19l-2.25-1.25L14 21.5l-2-1.25l-2 1.25l-2.25-1.25L5.5 21.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ti9h6i7qm {
  d: path("M9.75 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M12 9.75v6.75m0-3h2.25m-2.25 3h2.25");
}

</style>
