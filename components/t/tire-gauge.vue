<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ku69a1bjs"/><path class="gbcjlhdil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tire-gauge" /></template>
<style>
.gbcjlhdil {
  d: path("M16.5 17.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ku69a1bjs {
  d: path("M15.596 6.404za2.25 2.25 0 0 1 0 3.182l-4.95 4.95a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182l4.95-4.95a2.25 2.25 0 0 1 3.182 0m2.122-2.122l-2.122 2.122m-8.132 8.132l-3.182 3.182m9.468-.218a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
