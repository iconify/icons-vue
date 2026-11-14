<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ou0pysx4u"/><path class="ttivdybds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pda" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ou0pysx4u {
  d: path("M6.875 2.5h3.75A4.375 4.375 0 0 1 15 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-3.75A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5");
}

.ttivdybds {
  d: path("M7.25 5.5h3A1.75 1.75 0 0 1 12 7.25v3A1.75 1.75 0 0 1 10.25 12h-3a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 7.25 5.5m0 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M21 3.5l-3 17");
}

</style>
