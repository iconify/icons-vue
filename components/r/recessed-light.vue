<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsfr4abax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recessed-light" /></template>
<style>
.gsfr4abax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5m-14 0h9.5V7.5a2 2 0 0 1-2 2h-5.5a2 2 0 0 1-2-2Zm4.75 6.5v3.5M7.75 12l-2 2.75M16.25 12l2 2.75");
}

</style>
