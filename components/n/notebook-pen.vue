<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="on91mtwzt"/><path class="cu0muothe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:notebook-pen" /></template>
<style>
.cu0muothe {
  d: path("M15.828 9.172za1 1 0 0 1 0 1.414l-3.568 3.568a1.5 1.5 0 0 1-.766.41l-.439.088a.6.6 0 0 1-.707-.707l.088-.439a1.5 1.5 0 0 1 .41-.766l3.568-3.568a1 1 0 0 1 1.414 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.on91mtwzt {
  d: path("M9.5 3h7A3.5 3.5 0 0 1 20 6.5v11a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 6 17.5v-11A3.5 3.5 0 0 1 9.5 3M4 7.5h4M4 12h4m-4 4.5h4");
}

</style>
