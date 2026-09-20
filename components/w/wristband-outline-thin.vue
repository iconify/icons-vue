<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pp_u7qguw"/><path class="vcln6n2xe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wristband-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pp_u7qguw {
  d: path("M14 6c4 1 7 3 7 6 0 4 -4 6 -9 6s-9 -2 -9 -6c0 -3 3 -5 7 -6");
}

.vcln6n2xe {
  d: path("M10 3h4v5h-4Z");
}

</style>
