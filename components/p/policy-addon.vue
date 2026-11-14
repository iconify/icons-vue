<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fqqbicbmi"/><path class="tpcgjfolm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:policy-addon" /></template>
<style>
.fqqbicbmi {
  d: path("M13.778 20.5H5v-18h8.5L19 8v4.422");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tpcgjfolm {
  d: path("M13.5 2.5V8H19M8.5 12h7m-7 4h3m6.5-1v6m-3-3h6");
}

</style>
