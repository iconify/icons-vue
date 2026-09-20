<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6eri9pjq"/><path class="ta4vmeb9o"/><path class="o0lh1k1dl"/><path class="hf1bs3jrv"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="jlfjgzbqx"/><path class="kvfieo68l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prefix-cache-duotone-thin" /></template>
<style>
.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.e6eri9pjq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hf1bs3jrv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 11 11 13.5h2.5L11 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlfjgzbqx {
  d: path("M9 9h6");
}

.kvfieo68l {
  d: path("M13.5 11 11 13.5h2.5L11 16");
}

.o0lh1k1dl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ta4vmeb9o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
