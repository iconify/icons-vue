<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hpy_80lju"/><path class="kgzfjfb2m"/><path class="mglly3fuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stack-trace-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hpy_80lju {
  d: path("M3 3v18h8");
}

.kgzfjfb2m {
  d: path("M9 7v10h6");
}

.mglly3fuq {
  d: path("M15 10v3h4");
}

</style>
