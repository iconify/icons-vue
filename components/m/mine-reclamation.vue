<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gye0i4b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-reclamation" /></template>
<style>
.gye0i4b5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5C6 16 18 16 21.5 20.5ZM12 17V7m0 5c-3.5 0-5-2.5-5-5c2.5 0 5 1.5 5 5m0-2.5c0-3.5 2.5-6 5-6c0 2.5-1.5 6-5 6m-10 11h20");
}

</style>
