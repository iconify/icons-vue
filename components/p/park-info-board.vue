<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld727xb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:park-info-board" /></template>
<style>
.ld727xb7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v7.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 13.875v-7.75A2.625 2.625 0 0 1 5.125 3.5M7 16.5L5 21m12-4.5l2 4.5M12 7h.01M12 9.75v3.75");
}

</style>
