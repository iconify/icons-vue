<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q11q8pbau"/><path class="a9_g1_bko"/><path class="btex5sb2a"/><path class="h3s_qfbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-heading-broken" /></template>
<style>
.a9_g1_bko {
  d: path("M5 18V22");
}

.btex5sb2a {
  d: path("M19 2V22");
}

.h3s_qfbzc {
  d: path("M5 12H19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q11q8pbau {
  d: path("M5 2V14");
}

</style>
