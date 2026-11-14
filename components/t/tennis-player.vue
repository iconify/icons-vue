<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyql-czxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-player" /></template>
<style>
.wyql-czxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M2.5 21.5C2.5 17 5 14.75 8 14.75s5.5 2.25 5.5 6.75m1-14.75a3.5 4.75 0 1 0 7 0a3.5 4.75 0 1 0-7 0M18 11.5V18m0-16v9.5m-3.5-4.75h7");
}

</style>
