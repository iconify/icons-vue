<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dtnckfvpc"/><path class="aopv0ke_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:running" /></template>
<style>
.aopv0ke_q {
  d: path("m19.25 9.5l-2.25 2L14 9l-3.75 1.25l-2.25 3");
}

.dtnckfvpc {
  d: path("M14 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M14 9l-2.25 5.5l4 2.5l-.75 4.5m-3.25-7L9 18.25l-4.25.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
