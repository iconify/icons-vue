<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="tdjjhsyrl"/><path class="jqicofoha"/><path class="tai7-ubtf"/><path class="r5j1nz2jb"/><path class="eooj7sbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-journey-sharp" /></template>
<style>
.eooj7sbat {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 19.5h.01");
}

.jqicofoha {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 16H21v-.5c0-2-2-3-4.5-3s-4.5 1-4.5 3v.5z");
}

.r5j1nz2jb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7v5.5h5v7H14");
}

.tai7-ubtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.5 4.5h.01");
}

.tdjjhsyrl {
  cx: 16.5px;
  cy: 7px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
