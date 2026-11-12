<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="o_onwfy1m"/><ellipse class="u38oezbao"/><path class="sfxgh6bez"/><path class="d8f9mr75j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-speak-rounded-line-duotone" /></template>
<style>
.d8f9mr75j {
  d: path("M17 4C17 4 18 4.6 18 6C18 7.4 17 8 17 8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_onwfy1m {
  cx: 10px;
  cy: 6px;
  r: 4px;
}

.sfxgh6bez {
  d: path("M19 2C19 2 21 3.2 21 6C21 8.8 19 10 19 10");
}

.u38oezbao {
  cx: 10px;
  cy: 17px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 7px;
  ry: 4px;
}

</style>
