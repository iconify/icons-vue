<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rr_9skpht"/><path class="nqd_99bcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paper-towel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nqd_99bcy {
  d: path("M5.5 2.5h13a2.5 4.5 0 0 1 0 9h-13m4 0v9l2-1l2 1.5l2-1.5l2 1.5v-9.5");
}

.rr_9skpht {
  d: path("M3 7a2.5 4.5 0 1 0 5 0a2.5 4.5 0 1 0-5 0");
}

</style>
