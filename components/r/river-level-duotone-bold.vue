<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="buk14h7lm"/><path class="rdxzm_gti"/><path class="f1-cuq71c"/><path class="o2o7qi0tg"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="f3zridcmg"/><path class="z_c7updjp"/><path class="m0msdy1bm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:river-level-duotone-bold" /></template>
<style>
.buk14h7lm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f1-cuq71c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f3zridcmg {
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
}

.m0msdy1bm {
  d: path("M5 11h4");
}

.o2o7qi0tg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.rdxzm_gti {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ws1d0fbts {
  d: path("M20 4v16");
}

.z_c7updjp {
  d: path("M5 8h4");
}

</style>
