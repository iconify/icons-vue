<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqb-ezt6n"/><path class="qfknm1bfo"/><path class="tys_c3bfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mfa-push-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qfknm1bfo {
  d: path("M7.5 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.tys_c3bfo {
  d: path("m16 11 2 2 3 -3");
}

.wqb-ezt6n {
  d: path("M4 4a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
