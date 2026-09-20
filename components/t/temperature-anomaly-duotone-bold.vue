<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="kba2rfftw"/><path class="q_ppqibnu"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="nyl8f3o_r"/><path class="bxgmjusbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:temperature-anomaly-duotone-bold" /></template>
<style>
.bxgmjusbj {
  d: path("m6 17 4 -4 3 3 4 -4");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kba2rfftw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 13h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nyl8f3o_r {
  d: path("M6 13h13");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.q_ppqibnu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 17 4 -4 3 3 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
