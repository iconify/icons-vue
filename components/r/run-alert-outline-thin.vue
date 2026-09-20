<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="brpj2xbjm"/><path class="bskrurb1h"/><path class="s8vehckhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:run-alert-outline-thin" /></template>
<style>
.brpj2xbjm {
  d: path("M4 5v14l7 -7Z");
}

.bskrurb1h {
  d: path("M18 7v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s8vehckhm {
  d: path("M17 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
