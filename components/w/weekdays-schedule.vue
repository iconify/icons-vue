<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl4g2dl4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weekdays-schedule" /></template>
<style>
.bl4g2dl4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v9.5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5V8A3.5 3.5 0 0 1 6 4.5m2-2v4m8-4v4m-10.5 7h.01m3.24 0h.01m3.24 0h.01m3.24 0h.01m3.24 0h.01");
}

</style>
