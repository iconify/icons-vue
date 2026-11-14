<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fbf28eboe"/><path class="lpmq4tukk"/><path class="dgthpbcoi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-offer" /></template>
<style>
.dgthpbcoi {
  d: path("m9.486 7.554l1.5-1.375a1.5 1.5 0 0 1 2.028 0l1.5 1.375A1.5 1.5 0 0 1 15 8.66v.84a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 9.5v-.84a1.5 1.5 0 0 1 .486-1.106");
}

.fbf28eboe {
  d: path("M2.5 12v7.5a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpmq4tukk {
  d: path("m2.5 12l9.5 5.5l9.5-5.5M5 11.5V4a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 19 4v7.5");
}

</style>
