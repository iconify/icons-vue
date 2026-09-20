<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="njs8q8bsp"/><path class="zy54a7bml"/><path class="zl61012kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swipe-action-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.njs8q8bsp {
  d: path("M3 9a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.zl61012kd {
  d: path("M18.5 9.5 21 12l-2.5 2.5");
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
