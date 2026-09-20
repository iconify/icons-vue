<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b9dlqfb3c"/><path class="bb5b1huej"/><path class="te6wlfhwg"/><path class="hb0ic8bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:materialized-view-duotone-thin" /></template>
<style>
.b9dlqfb3c {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.bb5b1huej {
  fill: currentColor;
  d: path("M7 9a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hb0ic8bmn {
  d: path("M7 9a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.te6wlfhwg {
  d: path("M2 5a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
