<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rutznm-0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sample-cooler" /></template>
<style>
.rutznm-0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8h11a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18v-6.5A3.5 3.5 0 0 1 6.5 8M3 11.5h18M8 8V5c0-1.1.9-2 2-2h4c1.1 0 2 .9 2 2v3m-4 6v5m2.165-3.75l-4.33 2.5m0-2.5l4.33 2.5");
}

</style>
