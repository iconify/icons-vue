<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fkayfqbji"/><path class="nu0ti3ggl"/><path class="hh3je2bri"/><path class="qor244zue"/><path class="vhnbtvbtn"/><path class="jyd5g773m"/><path class="d_scobift"/><path class="u-x8-1cug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:relevance-score-duotone-bold" /></template>
<style>
.d_scobift {
  d: path("M3 18h6");
}

.fkayfqbji {
  fill: currentColor;
  d: path("M17 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hh3je2bri {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jyd5g773m {
  d: path("M3 13h12");
}

.nu0ti3ggl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qor244zue {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-x8-1cug {
  d: path("M17 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

</style>
