<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo_b0b69o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prison-bars" /></template>
<style>
.zo_b0b69o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5m-18.5 17.5h18.5M5.5 3.25v17.5m4.25-17.5v17.5m4.5-17.5v17.5m4.25-17.5v17.5m-13-9.5h13");
}

</style>
