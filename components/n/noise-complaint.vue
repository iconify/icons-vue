<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw7ih-gis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:noise-complaint" /></template>
<style>
.bw7ih-gis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 8.5h1.525a1.75 1.75 0 0 0 1.238-.513L9 6a1.464 1.464 0 0 1 2.5 1.036v9.928A1.464 1.464 0 0 1 9 18l-1.987-1.987a1.75 1.75 0 0 0-1.238-.513H4.25a1.75 1.75 0 0 1-1.75-1.75v-3.5A1.75 1.75 0 0 1 4.25 8.5m10.078.672a4 4 0 0 1 .931 4.196m1.062-7.113a7.5 7.5 0 0 1 2.65 6.399m-3.538 6.638l1.245-2.324a1.5 1.5 0 0 1 2.644 0l1.245 2.324a1.5 1.5 0 0 1-1.322 2.208h-2.49a1.5 1.5 0 0 1-1.322-2.208M18 17.75v1.75");
}

</style>
