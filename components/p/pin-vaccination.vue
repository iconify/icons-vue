<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bde6l8plb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-vaccination" /></template>
<style>
.bde6l8plb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.581 12.177l4.596-4.596a1.75 1.75 0 0 1 2.475 0l1.767 1.767a1.75 1.75 0 0 1 0 2.475l-4.596 4.596a1.75 1.75 0 0 1-2.475 0l-1.767-1.767a1.75 1.75 0 0 1 0-2.475m-4.42 4.419l4.243 4.243m-2.122-2.121l3.182-3.182m7.072-7.072l3.182-3.182m-9.9 5.657l1.768 1.768m.353-3.889l1.768 1.768");
}

</style>
