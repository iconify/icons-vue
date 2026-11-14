<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="votg0xsnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:public-broadcaster-tower" /></template>
<style>
.votg0xsnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 21.5l5-10.25l5 10.25m-5-13h.01m3.49-3a4.5 4.5 0 0 1 0 6m-7-6a4.5 4.5 0 0 0 0 6M18 3.25a8 8 0 0 1 0 10.5M6 3.25a8 8 0 0 0 0 10.5");
}

</style>
