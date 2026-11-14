<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ujq-3fbzc"/><path class="h5bbwubbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:slide-stain" /></template>
<style>
.h5bbwubbs {
  d: path("M13 9.25c1 1.25 2 2.25 2 3.5a2 2 0 0 1-4 0c0-1.25 1-2.25 2-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ujq-3fbzc {
  d: path("M4.621 6.5h14.758a1.5 1.5 0 0 1 1.06.439l.622.622a1.5 1.5 0 0 1 .439 1.06v6.758a1.5 1.5 0 0 1-.439 1.06l-.622.622a1.5 1.5 0 0 1-1.06.439H4.621a1.5 1.5 0 0 1-1.06-.439l-.622-.622a1.5 1.5 0 0 1-.439-1.06V8.621a1.5 1.5 0 0 1 .439-1.06l.622-.622a1.5 1.5 0 0 1 1.06-.439m1.879 0v11");
}

</style>
