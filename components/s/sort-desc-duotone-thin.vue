<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7h8iyqlm"/><path class="di-mwobgn"/><path class="jv75tobai"/><path class="k4qo1xe9v"/><path class="xlekzhbnl"/><path class="vybq366mg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sort-desc-duotone-thin" /></template>
<style>
.b7h8iyqlm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.di-mwobgn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jv75tobai {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.vybq366mg {
  d: path("M4 18h6");
}

.xlekzhbnl {
  d: path("M4 12h11");
}

</style>
