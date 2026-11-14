<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwmtucrwt"/><path class="r4-gfihlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:surface-tension" /></template>
<style>
.cwmtucrwt {
  d: path("M12 4.25c-3 4-6.5 8-6.5 11.5c0 2.25 1 4 2.5 4h8c1.5 0 2.5-1.75 2.5-4c0-3.5-3.5-7.5-6.5-11.5m-9.5 15.5h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r4-gfihlw {
  d: path("M8.75 14.25C8.75 16 9.75 17 11 17");
}

</style>
