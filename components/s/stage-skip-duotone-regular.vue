<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5v54kp1e"/><path class="e8pwa3bwv"/><path class="vy7jk_b7v"/><path class="ri2m-q_tv"/><path class="f6g4tkbvw"/><path class="coi-np7dk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stage-skip-duotone-regular" /></template>
<style>
.coi-np7dk {
  d: path("M15 9v6");
}

.e8pwa3bwv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f6g4tkbvw {
  d: path("m9 9 3 3 -3 3");
}

.n5v54kp1e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.vy7jk_b7v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
