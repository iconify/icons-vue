<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="onacf9b6c"/><path class="o4eziwo1l"/><path class="j7rh_c0kj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vision-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7rh_c0kj {
  d: path("m8.5 18.5l3-4l3 4m.25-5.25h.01");
}

.o4eziwo1l {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.75 5.5h7.5a1.75 1.75 0 0 1 1.75 1.75v4.5a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75v-4.5a1.75 1.75 0 0 1 1.75-1.75");
}

.onacf9b6c {
  d: path("M6 7h12a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-7.5A3.5 3.5 0 0 1 6 7");
}

</style>
