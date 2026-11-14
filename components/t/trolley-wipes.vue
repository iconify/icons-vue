<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a45tvr3oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trolley-wipes" /></template>
<style>
.a45tvr3oc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H5l2.25 10H17l2-7H5.75m-1 11.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.75 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.5-2.25q.5 2.25 2.75 2.75q-2.25.5-2.75 2.75q-.5-2.25-2.75-2.75Q18.5 18 19 15.75");
}

</style>
