<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-6jm1hpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sweeping" /></template>
<style>
.n-6jm1hpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.75 3.773l-4.25 7.361m-1.815-1.048l3.63 2.096a1.75 1.75 0 0 1 .795 2.041l-1.692 5.374a1.75 1.75 0 0 1-2.544.99l-5.748-3.318a1.75 1.75 0 0 1-.414-2.698l3.808-4.153a1.75 1.75 0 0 1 2.165-.332m-1.201 2.771l-3.433 4.946m6.465-3.196l-2.567 5.446M3 17h.01m1.49 3.5h.01");
}

</style>
