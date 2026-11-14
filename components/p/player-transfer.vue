<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t371rjb0l"/><path class="o-2batzed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:player-transfer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o-2batzed {
  d: path("M15.25 5.5L18 6l.5-2.75");
}

.t371rjb0l {
  d: path("M3.5 11.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m12 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M2.5 21a3.5 3.5 0 0 1 7 0m5 0a3.5 3.5 0 0 1 7 0M6 6a7.5 7.5 0 0 1 12 0");
}

</style>
