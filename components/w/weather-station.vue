<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0ywrxbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:weather-station" /></template>
<style>
.z0ywrxbnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.53 3.04l6.69 3.67q.53.29-.07.29h-.05q-.6 0-.6.6v7.8q0 .6-.6.6H6.1q-.6 0-.6-.6V7.6q0-.6-.6-.6h-.05q-.6 0-.07-.29l6.69-3.67q.53-.29 1.06 0M5.5 10h13m-13 3h13M7.75 16v5.25m8.5-5.25v5.25");
}

</style>
