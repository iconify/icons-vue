<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="caxy408kc"/><path class="jy2yhfbpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shop-window-display" /></template>
<style>
.caxy408kc {
  d: path("M5.25 2.5h13.5a1.75 1.75 0 0 1 1.75 1.75v13A1.75 1.75 0 0 1 18.75 19H5.25a1.75 1.75 0 0 1-1.75-1.75v-13A1.75 1.75 0 0 1 5.25 2.5M2.5 19h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jy2yhfbpw {
  d: path("M10.25 6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-2 4.5c0-1.25 1.25-1.75 3.75-1.75s3.75.5 3.75 1.75c-.5 1.5-1.75 2-1.75 4h-4c0-2-1.25-2.5-1.75-4m3.75 4v2.25m-2 0h4");
}

</style>
