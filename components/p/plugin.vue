<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0jfq0bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plugin" /></template>
<style>
.u0jfq0bmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.75h3.5a2 2 0 1 1 3.5 0h2a2 2 0 0 1 2 2v2.5a2 2 0 1 1 0 3.5v3a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2m12.75-5q.3 2.2 2.5 2.5q-2.2.3-2.5 2.5q-.3-2.2-2.5-2.5q2.2-.3 2.5-2.5");
}

</style>
