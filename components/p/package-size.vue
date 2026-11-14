<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_pqjob0h"/><path class="czugb3f-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:package-size" /></template>
<style>
.czugb3f-q {
  d: path("m4 6.5l8 4l8-4m-8 4v7m-8 3h16M4 19v3m16-3v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_pqjob0h {
  d: path("m12.783 2.891l6.25 3.125A1.75 1.75 0 0 1 20 7.582v4.836a1.75 1.75 0 0 1-.967 1.566l-6.25 3.125a1.75 1.75 0 0 1-1.566 0l-6.25-3.125A1.75 1.75 0 0 1 4 12.418V7.582a1.75 1.75 0 0 1 .967-1.566l6.25-3.125a1.75 1.75 0 0 1 1.566 0");
}

</style>
