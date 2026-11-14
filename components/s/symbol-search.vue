<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_s12eb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:symbol-search" /></template>
<style>
.k_s12eb8r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5H8a2 2 0 0 0-2 2V7L4 8.5L6 10v2.5a2 2 0 0 0 2 2h.5m5-12h.5q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T16 4.5V7l2 1.5l-2 1.5v.472M13.25 16.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m5.5 2.25L21 21");
}

</style>
