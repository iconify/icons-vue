<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpcnk09be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roof-ladder" /></template>
<style>
.cpcnk09be {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5L9 11l10.5 10.5M12 10l7 7m2.25-2.25L11.5 5q-1.5-1.5-3 0l-1 1m6.5 6l2.25-2.25M17 15l2.25-2.25");
}

</style>
