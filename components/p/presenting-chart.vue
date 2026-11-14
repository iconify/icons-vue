<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saysmdlfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:presenting-chart" /></template>
<style>
.saysmdlfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21v-3.5c0-3 2-5 4.5-5c1.5 0 2.5.5 3.25 1.25L13 10M4 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm10 1.75l6.5-6.25m-5.25 19v-3m2.75 3v-7m2.75 7V17");
}

</style>
