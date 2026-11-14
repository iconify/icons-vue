<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz1t9lbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plantlet" /></template>
<style>
.iz1t9lbuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 19.25V11m0 3c-4 0-7.5-2.5-7.5-7c4 0 7.5 2.5 7.5 7m0-3c0-4.5 3.5-7.5 7.5-7.5C19.5 8 16 11 12 11M5 21q7-3.5 14 0");
}

</style>
