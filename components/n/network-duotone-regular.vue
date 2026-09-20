<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fsuht_b8c"/><path class="h68c8nomh"/><path class="ko36i74tu"/><path class="vt118ldin"/><path class="jr_i1wb2u"/><path class="izisgs3oo"/><path class="acyg6nb1v"/><path class="y99pnbb6w"/><path class="b6mgpfapj"/><path class="lx87koegb"/><path class="gz7owxbeh"/><path class="mow6v4bfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:network-duotone-regular" /></template>
<style>
.acyg6nb1v {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.b6mgpfapj {
  d: path("M17 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fsuht_b8c {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gz7owxbeh {
  d: path("m14 10 3 3");
}

.h68c8nomh {
  fill: currentColor;
  d: path("M3 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.izisgs3oo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 15h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jr_i1wb2u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 10 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ko36i74tu {
  fill: currentColor;
  d: path("M17 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lx87koegb {
  d: path("m10 10 -3 3");
}

.mow6v4bfc {
  d: path("M7.5 15h9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vt118ldin {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 10 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y99pnbb6w {
  d: path("M3 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
