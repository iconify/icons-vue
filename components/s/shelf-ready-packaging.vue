<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8fw73b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shelf-ready-packaging" /></template>
<style>
.e8fw73b2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 15h15.5a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 4.25 15m.25 0V9.5l1-1v-2h2v2l1 1V15m1.5 0V9.5l1-1v-2h2v2l1 1V15m1.5 0V9.5l1-1v-2h2v2l1 1V15M5.5 4.5h2m3.5 0h2m3.5 0h2M2.5 18h19");
}

</style>
