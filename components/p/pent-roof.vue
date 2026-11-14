<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z8ranvbbl"/><path class="dgwuiea8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pent-roof" /></template>
<style>
.dgwuiea8m {
  d: path("M4.5 7v13.5h15v-9.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8ranvbbl {
  d: path("m3.955 3.864l16.409 4.102A1.5 1.5 0 0 1 21.5 9.421v.329a1.17 1.17 0 0 1-1.455 1.136L3.636 6.784A1.5 1.5 0 0 1 2.5 5.329V5a1.17 1.17 0 0 1 1.455-1.136");
}

</style>
