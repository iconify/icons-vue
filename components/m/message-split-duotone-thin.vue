<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="znztjab3f"/><path class="n2f8q4bnc"/><path class="j4b_h1bvw"/><path class="oq62thbnf"/><path class="flj4c4ycb"/><path class="n-059ea3n"/><path class="vxqaiwbbu"/><path class="gcu5j9bzw"/><path class="wo23ajbmh"/><path class="rm0jxkbqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:message-split-duotone-thin" /></template>
<style>
.flj4c4ycb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 20h3v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gcu5j9bzw {
  d: path("M14 4h3v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4b_h1bvw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n-059ea3n {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n2f8q4bnc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 12 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oq62thbnf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 12 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rm0jxkbqz {
  d: path("M14 20h3v-3");
}

.vxqaiwbbu {
  d: path("m9 12 8 -8");
}

.wo23ajbmh {
  d: path("m9 12 8 8");
}

.znztjab3f {
  fill: currentColor;
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
