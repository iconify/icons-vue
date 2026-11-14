<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnyr47y-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nasal-spray" /></template>
<style>
.vnyr47y-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12.5h3a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18v-2A3.5 3.5 0 0 1 7 12.5m0-3h3a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 11A1.5 1.5 0 0 1 7 9.5m1.5 0h.723a1.5 1.5 0 0 0 1.225-.635l1.989-2.817a1.06 1.06 0 0 0-.187-1.423a.97.97 0 0 0-1.368.131L7.95 8.339A.711.711 0 0 0 8.5 9.5m6.75-6.25l4-1.25M16 6h5m-5.75 2.75l4 1.25");
}

</style>
