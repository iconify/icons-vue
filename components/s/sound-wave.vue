<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz_0qisdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sound-wave" /></template>
<style>
.kz_0qisdf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.25c1.5-6 3.5-6 4.75 0s3.25 6 4.75 0s3.5-6 4.75 0s3.25 6 4.75 0M3 18.25h18M18.75 16L21 18.25l-2.25 2.25");
}

</style>
