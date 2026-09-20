<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fsuht_b8c"/><path class="h68c8nomh"/><path class="ko36i74tu"/><path class="ylg4ahbeu"/><path class="g49r61jce"/><path class="dyf4o_bni"/><path class="acyg6nb1v"/><path class="y99pnbb6w"/><path class="b6mgpfapj"/><path class="lx87koegb"/><path class="gz7owxbeh"/><path class="mow6v4bfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:network-duotone-bold" /></template>
<style>
.acyg6nb1v {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.b6mgpfapj {
  d: path("M17 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dyf4o_bni {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 15h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fsuht_b8c {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g49r61jce {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 10 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y99pnbb6w {
  d: path("M3 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ylg4ahbeu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 10 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
