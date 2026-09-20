<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_lu0jbgc"/><path class="di-mwobgn"/><path class="lgv7os48g"/><path class="mt0duqbnk"/><path class="xlekzhbnl"/><path class="o8od38cnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sort-asc-duotone-thin" /></template>
<style>
.di-mwobgn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_lu0jbgc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lgv7os48g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mt0duqbnk {
  d: path("M4 6h6");
}

.o8od38cnm {
  d: path("M4 18h16");
}

.xlekzhbnl {
  d: path("M4 12h11");
}

</style>
