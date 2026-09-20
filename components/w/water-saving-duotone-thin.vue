<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gffvyfvho"/><path class="mepevqbwl"/><path class="u363cab-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:water-saving-duotone-thin" /></template>
<style>
.gffvyfvho {
  fill: currentColor;
  d: path("m12 4 6 6a6 6 0 0 1 -12 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mepevqbwl {
  d: path("m12 4 6 6a6 6 0 0 1 -12 0Z");
}

.u363cab-y {
  d: path("M5 19 19 5");
}

</style>
