<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hozsn7brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:order-cancelled" /></template>
<style>
.hozsn7brm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.666 20.648L12 21l-8.5-4.5v-9L12 3l8.5 4.5v5.165M3.5 7.5l6.01 3.182m4.949.016L20.5 7.5M12 12v2m3.5 1.5l5 5m0-5l-5 5");
}

</style>
