<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe2guabgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swap-vertical" /></template>
<style>
.fe2guabgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4.25v15.5m-3.5-3.5l3.5 3.5l3.5-3.5m5 3.5V4.25m-3.5 3.5l3.5-3.5l3.5 3.5");
}

</style>
