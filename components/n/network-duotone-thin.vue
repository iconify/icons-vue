<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fsuht_b8c"/><path class="h68c8nomh"/><path class="ko36i74tu"/><path class="kx6slobju"/><path class="vql1tob0i"/><path class="uyzrqvb4g"/><path class="acyg6nb1v"/><path class="y99pnbb6w"/><path class="b6mgpfapj"/><path class="lx87koegb"/><path class="gz7owxbeh"/><path class="mow6v4bfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:network-duotone-thin" /></template>
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko36i74tu {
  fill: currentColor;
  d: path("M17 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kx6slobju {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 10 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lx87koegb {
  d: path("m10 10 -3 3");
}

.mow6v4bfc {
  d: path("M7.5 15h9");
}

.uyzrqvb4g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.5 15h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vql1tob0i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 10 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y99pnbb6w {
  d: path("M3 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
