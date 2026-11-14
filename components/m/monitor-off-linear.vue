<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ca5qe4bzp"/><path class="dgu48p5zs"/><path class="kva043bzk"/><path class="w9gt9bbvf"/><path class="il3ef4b0z"/><path class="r-3me2efs"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-off-linear" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.ca5qe4bzp {
  d: path("M3.1716 3.17163C2 4.34313 2 6.22883 2 10V11C2 13.8284 2 15.2426 2.8787 16.1213C3.7574 17 5.1716 17 7.99999 17H8H16H16.0006C16.3548 17 16.6868 17 16.9983 16.9983");
}

.dgu48p5zs {
  d: path("M20.1561 16.7006C20.5426 16.5713 20.8562 16.3863 21.1212 16.1213C21.9999 15.2426 21.9999 13.8284 21.9999 11V10C21.9999 6.2288 21.9999 4.3431 20.8283 3.1716C19.6568 2 17.7711 2 13.9999 2H9.99993C8.10983 2 6.69333 2 5.60303 2.1475");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.il3ef4b0z {
  d: path("M22 13H16.4556");
}

.kva043bzk {
  d: path("M16 22H8");
}

.r-3me2efs {
  d: path("M13 13H2");
}

.w9gt9bbvf {
  d: path("M12 17V22");
}

</style>
