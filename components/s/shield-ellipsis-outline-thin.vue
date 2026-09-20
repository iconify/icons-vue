<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymp2b4b6u"/><path class="tn82r2bsv"/><path class="drftkjb-q"/><path class="pdux64boo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shield-ellipsis-outline-thin" /></template>
<style>
.drftkjb-q {
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pdux64boo {
  d: path("M14.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.tn82r2bsv {
  d: path("M7.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ymp2b4b6u {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
