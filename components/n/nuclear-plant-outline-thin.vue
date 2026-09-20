<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nk2bhslfp"/><path class="morp7_b7k"/><path class="dj0q8oblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nuclear-plant-outline-thin" /></template>
<style>
.dj0q8oblb {
  d: path("M12 2a2.5 2.5 0 0 1 0 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.morp7_b7k {
  d: path("M12 12a2.5 2.5 0 0 1 0 -5");
}

.nk2bhslfp {
  d: path("m7 20 2 -2V9h6v9l2 2Z");
}

</style>
