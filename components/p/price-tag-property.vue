<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p5ppq9bgr"/><path class="nj0c0v8gf"/><path class="iwj-9gb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-tag-property" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iwj-9gb7f {
  d: path("M11 8C9 5.5 6 4.5 3 6m5.5 9h7m-7 3h4");
}

.nj0c0v8gf {
  d: path("M10.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.p5ppq9bgr {
  d: path("m13.856 4.356l4.875 4.875a2.63 2.63 0 0 1 .769 1.856v7.788a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 18.875v-7.788a2.63 2.63 0 0 1 .769-1.856l4.875-4.875a2.625 2.625 0 0 1 3.712 0");
}

</style>
