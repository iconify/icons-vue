<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vph89qbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:publish-schedule" /></template>
<style>
.vph89qbzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.911 4.924L6.203 8.157A1.732 1.732 0 0 0 6 11.25l2.132 1.244A1.75 1.75 0 0 1 9 14.005v2.745a.952.952 0 0 0 1.789.454l5.337-9.831a1.75 1.75 0 0 0-2.215-2.449M9 13l9.5-10m-2 12.5h3.25a1.75 1.75 0 0 1 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75H16.5a1.75 1.75 0 0 1-1.75-1.75v-2.5a1.75 1.75 0 0 1 1.75-1.75m-1.75 2.75h6.75m-4.75-4.5v1.75m2.75-1.75v1.75");
}

</style>
