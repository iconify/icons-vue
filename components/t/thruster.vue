<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t07g5ub3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thruster" /></template>
<style>
.t07g5ub3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.66 8.58l5.18-2.41q.91-.42.91.58v10.5q0 1-.91.58l-5.18-2.41Q2.75 15 2.75 14v-4q0-1 .91-1.42m9.09-.08h2.5m3.5 0h2.5m-8.5 3.5h8.5m-8.5 3.5h2.5m3.5 0h2.5");
}

</style>
