<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oq4si96gj"/><path class="b6m1gwbvv"/><path class="q5dr00bah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pull-request-open" /></template>
<style>
.b6m1gwbvv {
  d: path("M18 7.25V11a4 4 0 0 1-4 4H9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oq4si96gj {
  d: path("M3.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m0 14a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M6 7.25v9.5M15.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.q5dr00bah {
  d: path("M11.75 12.75L9.5 15l2.25 2.25");
}

</style>
