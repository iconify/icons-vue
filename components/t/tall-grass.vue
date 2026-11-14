<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdg2ftbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tall-grass" /></template>
<style>
.pdg2ftbma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5h18m-14 0C7 14 5.5 8 3 3.5m9 18C12 14 12.5 8 14 3m3 18.5C17 15 18.5 10 21 6");
}

</style>
