<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tc3rjukod"/><path class="ac4p_wikp"/><path class="f2vh026ub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunglasses-outline-thin" /></template>
<style>
.ac4p_wikp {
  d: path("M14 9h7v5a3.5 3.5 0 0 1 -7 0Z");
}

.f2vh026ub {
  d: path("M10 9h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tc3rjukod {
  d: path("M3 9h7v5a3.5 3.5 0 0 1 -7 0Z");
}

</style>
