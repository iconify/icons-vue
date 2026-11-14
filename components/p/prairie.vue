<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw_x_rb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prairie" /></template>
<style>
.uw_x_rb1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19M6 20l-2.5-6M6 20v-8.5M6 20l2.5-6m6.5 6l-2.5-6m2.5 6v-9m0 9l2.5-6M16 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
