<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxnh-zzrn"/><path class="i3e_gmufr"/><path class="cdxjicbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refresh-ccw" /></template>
<style>
.cdxjicbsp {
  d: path("m15.5 15l3-3l3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3e_gmufr {
  d: path("m2.5 9l3 3l3-3m10 3a6.5 6.5 0 0 1-12.129 3.25");
}

.sxnh-zzrn {
  d: path("M5.5 12a6.5 6.5 0 0 1 12.129-3.25");
}

</style>
