<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-3vcsp9b"/><path class="l2od_-b7c"/><path class="hp-9o5-ku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:velocity" /></template>
<style>
.f-3vcsp9b {
  d: path("M2.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hp-9o5-ku {
  d: path("m17.5 3l3 3l-3 3");
}

.l2od_-b7c {
  d: path("M4.5 16.5c0-6 5.5-10.5 16-10.5");
}

</style>
