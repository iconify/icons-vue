<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="odvikjqzp"/><path class="jbvnzwbuo"/><path class="opskey5wx"/><path class="y07a50u1t"/><path class="ctb0q1bmb"/><path class="f1_59klhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rainwater-duotone-thin" /></template>
<style>
.ctb0q1bmb {
  d: path("m9 5 2 2a2 2 0 0 1 -4 0Z");
}

.f1_59klhv {
  d: path("m15 4 2 2a2 2 0 0 1 -4 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbvnzwbuo {
  fill: currentColor;
  d: path("m15 4 2 2a2 2 0 0 1 -4 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.odvikjqzp {
  fill: currentColor;
  d: path("m9 5 2 2a2 2 0 0 1 -4 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.opskey5wx {
  d: path("M7 13v7h10v-7");
}

.y07a50u1t {
  d: path("M5 13h14");
}

</style>
