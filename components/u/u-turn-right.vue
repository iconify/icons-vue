<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ngd_4va2s"/><path class="k9wk1abnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:u-turn-right" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9wk1abnv {
  d: path("m16.25 11.5l3.5 3.5l-3.5 3.5");
}

.ngd_4va2s {
  d: path("M20.25 5.5h-11a4.75 4.75 0 0 0 0 9.5h10.5");
}

</style>
