<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ksuxucb0r"/><path class="mg7aqnbsf"/><path class="anowge4lb"/><path class="jkuojibnm"/><path class="trk8friyx"/><path class="pqmht0bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sliding-window-duotone-thin" /></template>
<style>
.anowge4lb {
  d: path("M2 9.5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.ksuxucb0r {
  fill: currentColor;
  d: path("M2 9.5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.pqmht0bfn {
  d: path("m18 9.5 2 2 -2 2");
}

.trk8friyx {
  d: path("M16.5 12H19");
}

</style>
