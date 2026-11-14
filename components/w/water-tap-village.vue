<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khkuu8k4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-tap-village" /></template>
<style>
.khkuu8k4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5za2 2 0 0 1 2 2v15a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2m2 3h5a3 3 0 0 1 3 3v2m0 3.5S15 17 15 18.75a2.5 2.5 0 0 0 5 0C20 17 17.5 14 17.5 14");
}

</style>
