<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga_p20bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-air-pump" /></template>
<style>
.ga_p20bvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3h7M9 3v3m-.25 0h.5A1.75 1.75 0 0 1 11 7.75v9.5A1.75 1.75 0 0 1 9.25 19h-.5A1.75 1.75 0 0 1 7 17.25v-9.5A1.75 1.75 0 0 1 8.75 6M4.5 19h8.6M11 16.5q.532-.002.991-.123m3.252-6.368C15.185 8.295 14.723 6.723 14 6m4 15l-2.25-3.25a3.25 3.25 0 1 1 4.5 0Z");
}

</style>
