<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="putgnkb9b"/><path class="swj5iubgk"/><path class="mudg_ac9k"/><path class="xgrfb-bqu"/><path class="w8fmvxwit"/><path class="r3-lax2ik"/><path class="fu2iodbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mmr-duotone-thin" /></template>
<style>
.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fu2iodbya {
  d: path("M3 16h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mudg_ac9k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.putgnkb9b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3-lax2ik {
  d: path("m8 9 4 4");
}

.swj5iubgk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 9 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w8fmvxwit {
  d: path("M3 11h14");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
