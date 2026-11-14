<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiqyctb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pantry-shelf" /></template>
<style>
.jiqyctb1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19m-19 10h19m-17-10V6A1.5 1.5 0 0 1 6 4.5v-2h3v2A1.5 1.5 0 0 1 10.5 6v5m3 0V5h6v6M9 21v-4.5a1.5 1.5 0 0 1 1.5-1.5v-1.25h3V15a1.5 1.5 0 0 1 1.5 1.5V21");
}

</style>
