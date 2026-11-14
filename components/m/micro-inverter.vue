<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egt3rp1rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:micro-inverter" /></template>
<style>
.egt3rp1rv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.366 3h11.393a1.75 1.75 0 0 1 1.697 2.174l-1.625 6.5A1.75 1.75 0 0 1 17.134 13H5.741a1.75 1.75 0 0 1-1.697-2.174l1.625-6.5A1.75 1.75 0 0 1 7.366 3M4.75 8h15M13.5 3L11 13m6 0v3.5m-1.25 0h2.5A1.75 1.75 0 0 1 20 18.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 14 19.75v-1.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
