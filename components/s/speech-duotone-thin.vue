<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yh9u2vb-g"/><path class="r63slnb7d"/><path class="syr202grk"/><path class="a4habeb9x"/><path class="jfpn1_rdc"/><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="h7bcztycq"/><path class="cg-q-7bgo"/><path class="om2raabrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speech-duotone-thin" /></template>
<style>
.a4habeb9x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cg-q-7bgo {
  d: path("M16 3v18");
}

.el0n_ccnv {
  d: path("M8 5v14");
}

.h7bcztycq {
  d: path("M12 8v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfpn1_rdc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lbz2yq5no {
  d: path("M4 9v6");
}

.om2raabrv {
  d: path("M20 10v4");
}

.r63slnb7d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.syr202grk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yh9u2vb-g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
