<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltyomhpzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trumpet" /></template>
<style>
.ltyomhpzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.8 9.89l3.65-3.53q.8-.61.8.39v10.5q0 1-.8.39l-3.65-3.53q-.8-.61-.8-1.61v-1q0-1 .8-1.61M2.75 12H16M2.75 10.5v3m3-1.5v3.25A2.25 2.25 0 0 0 8 17.5h3a2.25 2.25 0 0 0 2.25-2.25V12m-5.5 0V7.75M10.5 12V7.75M13.25 12V7.75M7 7.75h1.5m1.25 0h1.5m1.25 0H14");
}

</style>
