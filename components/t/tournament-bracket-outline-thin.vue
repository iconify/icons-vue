<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rdhgnbc4d"/><path class="qno8l4b9z"/><path class="nuz6-76is"/><path class="l3ca9u8kt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tournament-bracket-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3ca9u8kt {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nuz6-76is {
  d: path("M15 12h6");
}

.qno8l4b9z {
  d: path("M3 19h6v-7");
}

.rdhgnbc4d {
  d: path("M3 5h6v7h6");
}

</style>
