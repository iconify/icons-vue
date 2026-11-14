<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yo_qlvbhb"/><path class="uomljl7-q"/><path class="xt-cy3bnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recycle-bottle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uomljl7-q {
  d: path("M5.5 11.5a9.5 3.5 0 0 0-3 2.5a9.5 3.5 0 0 0 19 0a9.5 3.5 0 0 0-3-2.5");
}

.xt-cy3bnc {
  d: path("m11 16.25l1.25 1.25L11 18.75");
}

.yo_qlvbhb {
  d: path("M10.25 2.5h3.5v2.75L16 8v11.5a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2V8l2.25-2.75Z");
}

</style>
