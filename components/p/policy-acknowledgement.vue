<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duf3-fbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:policy-acknowledgement" /></template>
<style>
.duf3-fbmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4H13M2.5 7.5h9m-9 3.5H8m10.718-6.425l.707.707a1.5 1.5 0 0 1 0 2.122l-7.104 7.103a1.5 1.5 0 0 1-.766.41l-1.323.265a1.202 1.202 0 0 1-1.414-1.414l.265-1.323a1.5 1.5 0 0 1 .41-.766l7.103-7.104a1.5 1.5 0 0 1 2.122 0M2.5 19c1-2.5 2.5-2.5 3-.5S7 20.5 8 18");
}

</style>
