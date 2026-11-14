<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="ic7mvn-lc"/><path class="ue4xr0uex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skin-type-combination" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic7mvn-lc {
  fill: currentColor;
  d: path("M9.5 6.5h5a1.5 1.5 0 0 1 0 3h-1v5a1.5 1.5 0 0 1-3 0v-5h-1a1.5 1.5 0 0 1 0-3");
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.ue4xr0uex {
  d: path("M7.5 11.5h.01m8.99 0h.01");
}

</style>
