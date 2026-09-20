<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="bxipa2bar"/><path class="s0-7f3bev"/><path class="mg_6zl_av"/><path class="k6nj2fbya"/><path class="r1-ktgx-e"/><path class="nmmozg1gr"/><path class="t33f_gbzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:outline-gen-duotone-bold" /></template>
<style>
.bxipa2bar {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.mg_6zl_av {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nmmozg1gr {
  d: path("M7 15h14");
}

.r1-ktgx-e {
  d: path("M7 10h14");
}

.s0-7f3bev {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t33f_gbzo {
  d: path("M11 20h10");
}

</style>
