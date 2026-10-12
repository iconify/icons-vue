<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_atexbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:screw" /></template>
<style>
.i_atexbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.75c0-2.4 2.5-4 6.25-4s6.25 1.6 6.25 4Zm4 0v9.75L12 20.75l2.25-4.25V6.75m-4.5 5l4.5-1.5m-4.5 5l4.5-1.5");
}

</style>
