<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw6opx86o"/><path class="e67s28gad"/><path class="rpp4spbxo"/><path class="szg40d_7w"/><path class="eoz5n0suo"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pool-duotone-thin" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.e67s28gad {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 11 2.5 -2.5L9 11l2.5 -2.5L14 11l2.5 -2.5L19 11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eoz5n0suo {
  d: path("m4 11 2.5 -2.5L9 11l2.5 -2.5L14 11l2.5 -2.5L19 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iw6opx86o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 7v8h20V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rpp4spbxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.szg40d_7w {
  d: path("M2 7v8h20V7");
}

</style>
