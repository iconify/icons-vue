<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jk_oqnb1z"/><path class="g1du9hbaz"/><path class="c438ceftc"/><path class="rvoc0ob8r"/><path class="es-ot3p7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:roundabout-duotone-thin" /></template>
<style>
.c438ceftc {
  d: path("M12 17v5");
}

.es-ot3p7v {
  d: path("M18 11h4");
}

.g1du9hbaz {
  d: path("M6 11a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jk_oqnb1z {
  fill: currentColor;
  d: path("M6 11a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rvoc0ob8r {
  d: path("M2 11h4");
}

</style>
