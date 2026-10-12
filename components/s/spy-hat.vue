<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k62a6vdps"/><path class="igtrnac2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spy-hat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.igtrnac2o {
  d: path("M8.5 15.75L12 20l3.5-4.25");
}

.k62a6vdps {
  d: path("m6.5 11.72l1.35-5.97A1.5 1.5 0 0 1 9.8 4.7l2.2.8l2.2-.8a1.5 1.5 0 0 1 1.95 1.05l1.35 5.97q-5.5 1.06-11 0m-3.75-.97q1.88.61 3.75.97m11 0q1.88-.36 3.75-.97M2.96 20.02l.08-.54q.21-1.23 1.3-1.84l2.32-1.28q1.09-.61 2.34-.61h6q1.25 0 2.34.61l2.32 1.28q1.09.61 1.3 1.84l.08.54q.21 1.23-1.04 1.23H4q-1.25 0-1.04-1.23");
}

</style>
