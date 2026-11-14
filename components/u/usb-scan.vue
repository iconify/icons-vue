<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftqfooq2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:usb-scan" /></template>
<style>
.ftqfooq2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9h3a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18v-5.5A3.5 3.5 0 0 1 8 9m-.25-6.5h3.5A1.75 1.75 0 0 1 13 4.25v3A1.75 1.75 0 0 1 11.25 9h-3.5A1.75 1.75 0 0 1 6 7.25v-3A1.75 1.75 0 0 1 7.75 2.5m.5 3.25h2.5m4.5 11.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
