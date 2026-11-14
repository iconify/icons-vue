<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aihkw_bqx"/><path class="rjnbwsbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:u-turn-bay" /></template>
<style>
.aihkw_bqx {
  d: path("M7 21.5V10a4 4 0 0 1 8 0v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjnbwsbax {
  d: path("m12 14l3 3l3-3M2.5 2.5v19m19-19v19");
}

</style>
