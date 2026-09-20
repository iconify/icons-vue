<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hxs7cr7lm"/><path class="grpcwaciz"/><path class="fy72pvbym"/><path class="bwel3nf-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-correct-outline-thin" /></template>
<style>
.bwel3nf-y {
  d: path("m16 15 2 2 3 -3");
}

.fy72pvbym {
  d: path("M4 16h10");
}

.grpcwaciz {
  d: path("m4 10 6 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxs7cr7lm {
  d: path("M4 7h10");
}

</style>
