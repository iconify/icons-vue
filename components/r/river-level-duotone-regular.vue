<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="cjx7a2bdd"/><path class="s4gag5t7u"/><path class="v6ewimfrm"/><path class="yzyen6bgh"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="f3zridcmg"/><path class="z_c7updjp"/><path class="m0msdy1bm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:river-level-duotone-regular" /></template>
<style>
.cjx7a2bdd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f3zridcmg {
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
}

.m0msdy1bm {
  d: path("M5 11h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.s4gag5t7u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v6ewimfrm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ws1d0fbts {
  d: path("M20 4v16");
}

.yzyen6bgh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z_c7updjp {
  d: path("M5 8h4");
}

</style>
