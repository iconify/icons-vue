<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5sodfc-y"/><path class="z43k13bxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tiny-house" /></template>
<style>
.c5sodfc-y {
  d: path("m3.939 9.561l4.5-4.5a1.5 1.5 0 0 1 2.122 0l4.5 4.5a1.5 1.5 0 0 1 .439 1.06V15a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 15v-4.379a1.5 1.5 0 0 1 .439-1.06M2.5 16.5h14l5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z43k13bxk {
  d: path("M7.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.5-3V13h2.5v3.5m4-4.5h.01");
}

</style>
