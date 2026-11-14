<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q620v5bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seabed" /></template>
<style>
.q620v5bcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5q2.375-2 4.75 0t4.75 0t4.75 0t4.75 0m-19 15h3c1-5.5 3.5-8 6.5-8s5.5 2.5 6.5 8h3");
}

</style>
