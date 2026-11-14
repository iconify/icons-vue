<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3kddbc9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pantry" /></template>
<style>
.f3kddbc9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5h19m-17 0v3m15-3v3M5.5 9zA2.5 2.5 0 0 1 8 11.5V16a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 3 16v-4.5A2.5 2.5 0 0 1 5.5 9M3 11.75h5m4.5-6.25za1.75 1.75 0 0 1 1.75 1.75v9.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-9.5A1.75 1.75 0 0 1 12.5 5.5m-1.75 3h3.5m4.75 3za2 2 0 0 1 2 2v3a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2M17 14h4");
}

</style>
