<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aja2g60he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-flosser" /></template>
<style>
.aja2g60he {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 19v-8c0-1.5 1-2.5 3-2.5s3 1 3 2.5v8A2.5 2.5 0 0 1 8 21.5H7A2.5 2.5 0 0 1 4.5 19m3-10.5v-3l3-3m-3 10v3m11-1.25L16 17a2.75 2.75 0 1 0 5 0Z");
}

</style>
