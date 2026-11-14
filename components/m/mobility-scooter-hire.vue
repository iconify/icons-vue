<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sk-wfsb1e"/><path class="dcn4ukbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mobility-scooter-hire" /></template>
<style>
.dcn4ukbus {
  d: path("M4.5 4v7.5H11m-2.5 0V16m-5.25 2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m11.75 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sk-wfsb1e {
  d: path("M3 16h11.5c1 0 1.5-.5 2-1.5L18.75 6M16 5.5h5");
}

</style>
