<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uktve7brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:offer-negotiation" /></template>
<style>
.uktve7brt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h5a1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 9 10H7l-2 2v-2H4a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 4 3m11 0h5a1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 20 10h-1v2l-2-2h-2a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 15 3M8.25 17a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M12 15.75v2.5");
}

</style>
