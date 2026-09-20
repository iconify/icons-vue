<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ksuxucb0r"/><path class="mg7aqnbsf"/><path class="anowge4lb"/><path class="jkuojibnm"/><path class="trk8friyx"/><path class="pqmht0bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sliding-window-duotone-regular" /></template>
<style>
.anowge4lb {
  d: path("M2 9.5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
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

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqmht0bfn {
  d: path("m18 9.5 2 2 -2 2");
}

.trk8friyx {
  d: path("M16.5 12H19");
}

</style>
