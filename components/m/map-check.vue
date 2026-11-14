<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2s9bwu9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-check" /></template>
<style>
.f2s9bwu9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.323 19.385L9 18l-6 2.5V6l6-2.5L15 6l6-2.5v9.4M9 3.5V18m6-12v3.25M14.75 18l2 2L21 15.75");
}

</style>
