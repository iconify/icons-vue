<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jra92rg5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skill-gap" /></template>
<style>
.jra92rg5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3h3A1.75 1.75 0 0 1 10 4.75v15a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-15A1.75 1.75 0 0 1 5.25 3m10 11h3A1.75 1.75 0 0 1 20 15.75v4a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 15.25 14m1.5-10.5V11m-2-5.5l2-2l2 2m-4 3.5l2 2l2-2");
}

</style>
