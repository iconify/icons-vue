<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j88foqvdl"/><path class="ms0p6sb1m"/><path class="mnj5l-bin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-pin-dot" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j88foqvdl {
  d: path("M12 17c-2.5-2.25-6.5-4.5-6.5-8a6.5 6.5 0 0 1 13 0c0 3.5-4 5.75-6.5 8");
}

.mnj5l-bin {
  fill: currentColor;
  d: path("M11 21a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.ms0p6sb1m {
  d: path("M9.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
