<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejkik-fut"/><path class="lds96gber"/><path class="c4axibc2h"/><path class="i2-ny_bzf"/><path class="yk993owos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:warm-start-duotone-thin" /></template>
<style>
.c4axibc2h {
  d: path("M8 3v4");
}

.ejkik-fut {
  fill: currentColor;
  d: path("M4 12a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.lds96gber {
  d: path("M4 12a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.yk993owos {
  d: path("M16 3v4");
}

</style>
