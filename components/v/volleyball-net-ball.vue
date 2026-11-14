<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="edqn41bac"/><path class="m_ik8sbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volleyball-net-ball" /></template>
<style>
.edqn41bac {
  d: path("M2.5 21.5v-8h19v8m-19-3h19M8 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.m_ik8sbqq {
  d: path("M12 6.5q1.25-2 0-4m0 4q1 2 3.5 2m-3.5-2q-2.25-.25-3.5 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
