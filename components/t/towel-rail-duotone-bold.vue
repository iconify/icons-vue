<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="n7e3snz5e"/><path class="g8eq-pu5e"/><path class="ib4yywb8r"/><path class="qamt0gbak"/><path class="k6nj2fbya"/><path class="kif6g-eik"/><path class="enh0e8a0v"/><path class="hczrfxb9f"/><path class="qtxvlht3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:towel-rail-duotone-bold" /></template>
<style>
.enh0e8a0v {
  d: path("M21 5v3");
}

.g8eq-pu5e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hczrfxb9f {
  d: path("M8 5v15h8V5");
}

.ib4yywb8r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 5v15h8V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.kif6g-eik {
  d: path("M3 5v3");
}

.n7e3snz5e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qamt0gbak {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qtxvlht3c {
  d: path("M8 17h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
