<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vq0uixb9a"/><path class="h3nfybbey"/><path class="vl-78uvmi"/><path class="i72p9bc3o"/><path class="rpp4spbxo"/><path class="k4wc6x-hq"/><path class="n_xjdobth"/><path class="ghuq2xb5p"/><path class="cjtmbcfpi"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:resort-duotone-thin" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.cjtmbcfpi {
  d: path("M13 18v-7h9v7");
}

.ghuq2xb5p {
  d: path("M10.5 12.5a3.5 3.5 0 0 1 0 -7");
}

.h3nfybbey {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3.5 5.5a3.5 3.5 0 0 1 0 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i72p9bc3o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 18v-7h9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k4wc6x-hq {
  d: path("M7 9v9");
}

.n_xjdobth {
  d: path("M3.5 5.5a3.5 3.5 0 0 1 0 7");
}

.rpp4spbxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vl-78uvmi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 12.5a3.5 3.5 0 0 1 0 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vq0uixb9a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
