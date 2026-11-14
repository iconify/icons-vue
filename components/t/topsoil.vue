<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z38k4o47r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:topsoil" /></template>
<style>
.z38k4o47r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10Q7 8 12 10t9.5 0m-19 10.5h19M7.5 15h.01m8.99.5h.01M12 10V4.5m0 3c0-2.5 2-4 4.5-4c0 2.5-2 4-4.5 4");
}

</style>
