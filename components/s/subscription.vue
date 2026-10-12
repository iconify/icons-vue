<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5m14rbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:subscription" /></template>
<style>
.f5m14rbsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 20.25h-4.5a2.5 2.5 0 0 1-2.5-2.5v-10a2.5 2.5 0 0 1 2.5-2.5h11.5a2.5 2.5 0 0 1 2.5 2.5v3M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5M17.25 14A3.25 3.25 0 1 1 14 17.25m-1.25 1.25L14 17.25l1.25 1.25");
}

</style>
