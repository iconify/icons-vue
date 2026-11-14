<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgwvx31yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:take-a-break" /></template>
<style>
.lgwvx31yn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h11v7a4 4 0 0 1-4 4h-3a4 4 0 0 1-4-4Zm11 1.5H15a2.5 2.5 0 0 1 0 5h-1.5M6 2.5V5m4-2.5V5m7.5 11.5v5m3-5v5");
}

</style>
