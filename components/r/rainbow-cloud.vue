<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ty1xtr7vj"/><path class="f2e_s_i9i"/><path class="zkfqurbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rainbow-cloud" /></template>
<style>
.f2e_s_i9i {
  d: path("M5.5 14.5a5.75 5.75 0 0 1 8.88-4.82");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ty1xtr7vj {
  d: path("M14.4 18a1.88 1.88 0 0 1-.26-3.75a2.7 2.7 0 0 1 5.01-.65a2.12 2.12 0 0 1-.28 4.4ZM2.75 14.5a8.5 8.5 0 0 1 15.2-5.23");
}

.zkfqurbrp {
  d: path("M8.25 14.5a3 3 0 0 1 3.83-2.88");
}

</style>
