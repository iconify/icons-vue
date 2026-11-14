<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb-idcg1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stern-flagstaff" /></template>
<style>
.tb-idcg1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14.5h18.5l-3 5.5h-14Zm3 0V3m0 .5c3-1 5 1.5 8.5.5v6C11 11 9 8.5 6 9.5");
}

</style>
