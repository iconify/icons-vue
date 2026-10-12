<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2a3qtbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-call" /></template>
<style>
.s2a3qtbpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.6 3.25h2.6a1 1 0 0 1 .95.68l1.1 3.3A1 1 0 0 1 10 8.25l-1.6 1.6a12.5 12.5 0 0 0 5.75 5.75l1.6-1.6a1 1 0 0 1 1.02-.25l3.3 1.1a1 1 0 0 1 .68.95v2.6a2.35 2.35 0 0 1-2.35 2.35c-8.3 0-15.15-6.85-15.15-15.15A2.35 2.35 0 0 1 5.6 3.25m8.9.5a6 6 0 0 1 5.75 5.75M14.5 7A2.75 2.75 0 0 1 17 9.5");
}

</style>
