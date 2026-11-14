<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k9_4tgb1k"/><path class="e9fgrydnp"/><path class="ecjiacbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mention" /></template>
<style>
.e9fgrydnp {
  d: path("M9.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.ecjiacbfy {
  d: path("M13.5 10v2.75a1.25 1.25 0 0 0 2.5 0V12a4.25 4.25 0 1 0-2 3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9_4tgb1k {
  d: path("m7.5 19.5l-3.5 1L5 17a8.5 8.5 0 1 1 2.5 2.5");
}

</style>
