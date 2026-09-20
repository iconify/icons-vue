<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws5wpblq"/><path class="s4802xbum"/><path class="u_5xtyu1s"/><path class="ri2m-q_tv"/><path class="f6g4tkbvw"/><path class="coi-np7dk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stage-skip-duotone-thin" /></template>
<style>
.coi-np7dk {
  d: path("M15 9v6");
}

.f6g4tkbvw {
  d: path("m9 9 3 3 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.s4802xbum {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u_5xtyu1s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vws5wpblq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
