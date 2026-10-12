<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt07c2b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pebble" /></template>
<style>
.jt07c2b4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 14.13zq.5-2.13 2.93-2.74l.14-.03q2.43-.61 3.93.77q1.5 1.37 1.25 3.25q-.25 1.87-2.74 2.07l-1.27.1Q5 17.75 3.88 17q-1.13-.75-.63-2.87m11 1.75zq.25-1.63 1.99-1.83l.77-.1q1.74-.2 2.98 1.04l.02.02q1.24 1.24.49 1.99t-2.5.67l-2.25-.09q-1.75-.08-1.5-1.7");
}

</style>
