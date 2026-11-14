<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu5jp3b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-gift" /></template>
<style>
.yu5jp3b_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.5h14.5A1.75 1.75 0 0 1 21 9.25v1A1.75 1.75 0 0 1 19.25 12H4.75A1.75 1.75 0 0 1 3 10.25v-1A1.75 1.75 0 0 1 4.75 7.5m0 4.5v7.75A1.25 1.25 0 0 0 6 21h12a1.25 1.25 0 0 0 1.25-1.25V12M12 7.5V21m0-13.5C11 4.5 9.5 3 8 3S6.25 4.5 7 5.5c1 1.25 3 2 5 2m0 0c1-3 2.5-4.5 4-4.5s1.75 1.5 1 2.5c-1 1.25-3 2-5 2");
}

</style>
