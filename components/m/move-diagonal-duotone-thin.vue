<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ireg5-o3k"/><path class="zpv32rbfe"/><path class="oo0zq0w3g"/><path class="emvotkb4z"/><path class="goxocdc6s"/><path class="i67dqei2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:move-diagonal-duotone-thin" /></template>
<style>
.emvotkb4z {
  d: path("M4 20 20 4");
}

.goxocdc6s {
  d: path("M10 4h10v10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i67dqei2u {
  d: path("M4 10v10h10");
}

.ireg5-o3k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oo0zq0w3g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10v10h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zpv32rbfe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 4h10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
