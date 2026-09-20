<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ddr0zpdgr"/><path class="uix68becb"/><path class="lkivjibuo"/><path class="q4rhaacat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunlight-outline-thin" /></template>
<style>
.ddr0zpdgr {
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkivjibuo {
  d: path("M12 13v7");
}

.q4rhaacat {
  d: path("m16 13 4 4");
}

.uix68becb {
  d: path("m8 13 -4 4");
}

</style>
