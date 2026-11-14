<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtyllsxre"/><path class="b8xgsabgj"/><path class="v0duv6bsv"/><path class="kva043bzk"/><path class="w9gt9bbvf"/><path class="eikhf2b4o"/><path class="r-3me2efs"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-off-broken" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.b8xgsabgj {
  d: path("M20.1564 16.7006C20.5429 16.5713 20.8565 16.3863 21.1215 16.1213C22.0002 15.2426 22.0002 13.8284 22.0002 11V10C22.0002 6.2288 22.0002 4.3431 20.8286 3.1716C19.6674 2.0103 17.8046 2.0001 14.0996 2");
}

.eikhf2b4o {
  d: path("M21.9995 13H16.4551");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtyllsxre {
  d: path("M3.1716 3.17163C2 4.34313 2 6.22883 2 10V11C2 13.8284 2 15.2426 2.8787 16.1213C3.7574 17 5.1716 17 7.99999 17H8H16H16.0006H16.0012C16.3552 17 16.687 17 16.9983 16.9983");
}

.kva043bzk {
  d: path("M16 22H8");
}

.r-3me2efs {
  d: path("M13 13H2");
}

.v0duv6bsv {
  d: path("M10.9004 2H10.0004C8.11032 2 6.69382 2 5.60352 2.1475");
}

.w9gt9bbvf {
  d: path("M12 17V22");
}

</style>
