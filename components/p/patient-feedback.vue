<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="khrb7na_d"/><path class="idqsu3b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patient-feedback" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.idqsu3b2w {
  d: path("m12 5.75l1.25 3h3l-2.25 2l.75 3.25L12 12.25L9.25 14l.75-3.25l-2.25-2h3Z");
}

.khrb7na_d {
  d: path("M4 5.5C4 4.1 5.1 3 6.5 3h11C18.9 3 20 4.1 20 5.5v9c0 1.4-1.1 2.5-2.5 2.5H10l-4.5 3.75v-4C4.6 16.5 4 15.6 4 14.5Z");
}

</style>
