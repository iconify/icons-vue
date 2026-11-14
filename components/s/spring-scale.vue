<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kstmhab0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spring-scale" /></template>
<style>
.kstmhab0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.125 5.5h1.75A2.625 2.625 0 0 1 15.5 8.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-1.75A2.625 2.625 0 0 1 8.5 13.875v-5.75A2.625 2.625 0 0 1 11.125 5.5m.875-3v3M8.5 9h2m-2 3.5h2m1-1.75h4M12 16.5v2a1.75 1.75 0 1 1-1.75 1.75");
}

</style>
