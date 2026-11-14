<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s4-gfacnn"/><path class="b9fyaubwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:relief-tent" /></template>
<style>
.b9fyaubwc {
  d: path("m6.5 18.5l3-7.5l2.534 6.334M18 21l-2.5-2.5A1.77 1.77 0 0 1 18 16a1.77 1.77 0 0 1 2.5 2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s4-gfacnn {
  d: path("M12.199 18.5H2.5c0-8.5 4-14 9-14c3.702 0 6.857 3.016 8.244 8.032");
}

</style>
