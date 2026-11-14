<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkdp1cbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-fail" /></template>
<style>
.pkdp1cbcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.087 2.5h5.826a2.63 2.63 0 0 1 1.856.769l3.962 3.962a2.63 2.63 0 0 1 .769 1.856v5.826a2.63 2.63 0 0 1-.769 1.856l-3.962 3.962a2.63 2.63 0 0 1-1.856.769H9.087a2.63 2.63 0 0 1-1.856-.769l-3.962-3.962a2.63 2.63 0 0 1-.769-1.856V9.087a2.63 2.63 0 0 1 .769-1.856l3.962-3.962A2.63 2.63 0 0 1 9.087 2.5M9 9l6 6m0-6l-6 6");
}

</style>
