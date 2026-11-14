<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o4oc42bwf"/><path class="k0qfvcbfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mushroom-grow-kit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0qfvcbfs {
  d: path("M8.5 14a3.5 3.5 0 0 1 7 0Zm3.5 0v4.5");
}

.o4oc42bwf {
  d: path("M6 2.5h12v3l1.5 3v11a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2v-11l1.5-3Zm0 3h12");
}

</style>
