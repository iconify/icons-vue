<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evucotbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:password-reveal" /></template>
<style>
.evucotbom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11a4 4 0 0 1 4 4a4 4 0 0 1-4 4h-11a4 4 0 0 1-4-4a4 4 0 0 1 4-4m1 4h.01m4.49 0h.01m4.49 0h.01M5.5 17.25C7 15 9.25 13.75 12 13.75s5 1.25 6.5 3.5c-1.5 2.25-3.75 3.5-6.5 3.5s-5-1.25-6.5-3.5m6.5 0h.01");
}

</style>
