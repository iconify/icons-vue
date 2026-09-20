<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e17y6ccrm"/><path class="wm7ubgban"/><path class="kn8jv2buv"/><path class="h7vr07ufd"/><path class="utlpmrn-a"/><path class="zx-f6ebvw"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="u1mon9cdo"/><path class="ze9yihd5h"/><path class="k-jt90-vx"/><path class="b-73d8bgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:partial-answer-duotone-bold" /></template>
<style>
.b-73d8bgy {
  d: path("M16 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e17y6ccrm {
  fill: currentColor;
  d: path("M6 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k-jt90-vx {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.kn8jv2buv {
  fill: currentColor;
  d: path("M16 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u1mon9cdo {
  d: path("M3 15h9");
}

.utlpmrn-a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wm7ubgban {
  fill: currentColor;
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x50q_4bdr {
  d: path("M3 10h18");
}

.ze9yihd5h {
  d: path("M6 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zx-f6ebvw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 15h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
