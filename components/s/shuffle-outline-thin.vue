<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fipykcbwt"/><path class="d210vyb8t"/><path class="ig2rw3qjx"/><path class="hs_3awbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shuffle-outline-thin" /></template>
<style>
.d210vyb8t {
  d: path("m18 13 3 3 -3 3");
}

.fipykcbwt {
  d: path("M3 7h6l9 9h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hs_3awbse {
  d: path("m18 5 3 3 -3 3");
}

.ig2rw3qjx {
  d: path("M3 17h6l9 -9h3");
}

</style>
