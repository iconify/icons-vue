<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gw2httbes"/><path class="bhihd6ztu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medical-record" /></template>
<style>
.bhihd6ztu {
  d: path("M5.5 14.5h3l1.5-3l2.5 6l1.5-3h4.5m0 0h.01");
}

.gw2httbes {
  d: path("M2.5 18.5v-13c0-1.1.9-2 2-2H9l2 2h8.5c1.1 0 2 .9 2 2v11c0 1.1-.9 2-2 2h-15c-1.1 0-2-.9-2-2m0-9.75h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
