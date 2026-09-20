<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qtb80hbdi"/><path class="pvffegb5k"/><path class="st2iv5bfu"/><path class="fxfo558wv"/><path class="t2kmfuk0y"/><path class="lb65jobfp"/><path class="pw61xnbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pram-duotone-thin" /></template>
<style>
.fxfo558wv {
  d: path("M4 13a8 8 0 0 1 16 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lb65jobfp {
  d: path("M7 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.pvffegb5k {
  fill: currentColor;
  d: path("M7 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pw61xnbei {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qtb80hbdi {
  fill: currentColor;
  d: path("M4 13a8 8 0 0 1 16 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.st2iv5bfu {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t2kmfuk0y {
  d: path("m4 13 4 4h12v-4");
}

</style>
