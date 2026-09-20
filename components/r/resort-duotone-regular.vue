<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s9-ej6p7q"/><path class="v94862moe"/><path class="j9_vt78qt"/><path class="csbiwd6ds"/><path class="xdhl9rnnf"/><path class="k4wc6x-hq"/><path class="n_xjdobth"/><path class="ghuq2xb5p"/><path class="cjtmbcfpi"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:resort-duotone-regular" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.cjtmbcfpi {
  d: path("M13 18v-7h9v7");
}

.csbiwd6ds {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 18v-7h9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ghuq2xb5p {
  d: path("M10.5 12.5a3.5 3.5 0 0 1 0 -7");
}

.j9_vt78qt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 12.5a3.5 3.5 0 0 1 0 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k4wc6x-hq {
  d: path("M7 9v9");
}

.n_xjdobth {
  d: path("M3.5 5.5a3.5 3.5 0 0 1 0 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s9-ej6p7q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v94862moe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3.5 5.5a3.5 3.5 0 0 1 0 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xdhl9rnnf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
