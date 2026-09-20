<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="advi1_bna"/><path class="e-e67f7pe"/><path class="kcb-pt73m"/><path class="bymggeinb"/><path class="a51oytv8p"/><path class="jz3tfobnp"/><path class="ur5cuwbiy"/><path class="op8_xbqqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:phishing-duotone-bold" /></template>
<style>
.a51oytv8p {
  d: path("M13 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.advi1_bna {
  fill: currentColor;
  d: path("M13 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.bymggeinb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 11v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e-e67f7pe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 6v9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jz3tfobnp {
  d: path("M15 6v9.5");
}

.kcb-pt73m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 15.5a4.5 4.5 0 0 1 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.op8_xbqqk {
  d: path("M6 11v4.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ur5cuwbiy {
  d: path("M15 15.5a4.5 4.5 0 0 1 -9 0");
}

</style>
