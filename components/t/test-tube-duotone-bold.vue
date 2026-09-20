<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b4gdm4amb"/><path class="v-ecc6-9c"/><path class="kp6e_l5bx"/><path class="kn820ue-q"/><path class="t3rzvj9ww"/><path class="sdu6a9xcp"/><path class="va9i39bae"/><path class="y07a50u1t"/><path class="pbz4y6llk"/><path class="c3wl0l-ou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:test-tube-duotone-bold" /></template>
<style>
.b4gdm4amb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 3v12l3 3 3 -3V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c3wl0l-ou {
  d: path("M19 13v6");
}

.kn820ue-q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kp6e_l5bx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pbz4y6llk {
  d: path("M5 13v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sdu6a9xcp {
  d: path("M9 3v12l3 3 3 -3V3");
}

.t3rzvj9ww {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-ecc6-9c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.va9i39bae {
  d: path("M7 3h10");
}

.y07a50u1t {
  d: path("M5 13h14");
}

</style>
