<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e_p_2qq0u"/><path class="hety6lbul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patient-transfer" /></template>
<style>
.e_p_2qq0u {
  d: path("M3 11v10m0-5.5h16.5c1.1 0 2 .9 2 2V21M3 18.75h18.5M5.5 9c2-5.5 11-5.5 13 0");
}

.hety6lbul {
  d: path("M16.25 8.25L18.5 9l.75-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
