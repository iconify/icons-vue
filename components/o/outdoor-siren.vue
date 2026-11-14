<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do1ktgbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:outdoor-siren" /></template>
<style>
.do1ktgbvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17v-4a5 5 0 0 1 10 0v4M6.25 17h11.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 17.75 21H6.25a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 6.25 17M12 2.5V5M4 6l1.75 1.75M20 6l-1.75 1.75");
}

</style>
