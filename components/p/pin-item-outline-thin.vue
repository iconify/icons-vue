<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6nj2fbya"/><path class="xa3jgydgh"/><path class="oumlmtbql"/><path class="zn_a46_dj"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pin-item-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.oumlmtbql {
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.xa3jgydgh {
  d: path("M3 12h9");
}

.zn_a46_dj {
  d: path("M18 12v3");
}

</style>
