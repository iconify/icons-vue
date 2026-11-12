<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="gp0egaclj"/><path class="mjwo7ebtq"/><path class="cs6wjacfk"/><path class="l9rlr6fkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:vinyl-line-duotone" /></template>
<style>
.cs6wjacfk {
  d: path("M15 2.45752C18.1101 3.43433 20.5654 5.88965 21.5422 8.99972");
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

.l9rlr6fkk {
  d: path("M15 11.9992V2.45703");
}

.mjwo7ebtq {
  d: path("M21.9506 12.9999C21.4489 18.0533 17.1853 21.9999 12 21.9999C6.47715 21.9999 2 17.5228 2 11.9999C2 6.81459 5.94668 2.55104 11 2.04932");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
