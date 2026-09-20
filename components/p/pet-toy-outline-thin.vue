<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uxyzhxvwz"/><path class="quv6fgbpo"/><path class="ezl2ndbvl"/><path class="oumlmtbql"/><path class="ap8hfz6rg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pet-toy-outline-thin" /></template>
<style>
.ap8hfz6rg {
  d: path("M16 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ezl2ndbvl {
  d: path("M4 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oumlmtbql {
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.quv6fgbpo {
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

</style>
