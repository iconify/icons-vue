<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="gp0egaclj"/><path class="lhqjqdqdz"/><path class="cfvlw8bpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:vinyl-linear" /></template>
<style>
.cfvlw8bpf {
  stroke-linejoin: round;
  d: path("M15 11.9997V2.45752C18.1101 3.43433 20.5654 5.88965 21.5422 8.99972");
}

.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhqjqdqdz {
  d: path("M21.9506 12.9999C21.4489 18.0533 17.1853 21.9999 12 21.9999C6.47715 21.9999 2 17.5228 2 11.9999C2 6.81459 5.94668 2.55104 11 2.04932");
}

</style>
