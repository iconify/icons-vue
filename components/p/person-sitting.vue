<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="obajmge2q"/><path class="d4bc8lb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-sitting" /></template>
<style>
.d4bc8lb7d {
  d: path("m7 9.5l3-.5l3.5 2M6 12v8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.obajmge2q {
  d: path("M8 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 4v5.5h5.5l1.5 7");
}

</style>
