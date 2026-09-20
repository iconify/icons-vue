<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rn5f9dbtw"/><path class="bjjj83beu"/><path class="ne8bcmb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:supplement-duotone-thin" /></template>
<style>
.bjjj83beu {
  d: path("M6 21V9h12v12Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ne8bcmb7x {
  d: path("M5 9V6h14v3");
}

.rn5f9dbtw {
  fill: currentColor;
  d: path("M6 21V9h12v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
