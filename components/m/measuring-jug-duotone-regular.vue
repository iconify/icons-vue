<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jmg_1z5qz"/><path class="hlr5flbgq"/><path class="qruk0ip3j"/><path class="aswuzmxao"/><path class="m_lxwabcp"/><path class="rsteb5bse"/><path class="did41pbsp"/><path class="jvpl-4ewk"/><path class="lymn1951z"/><path class="twn25-b-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:measuring-jug-duotone-regular" /></template>
<style>
.aswuzmxao {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.did41pbsp {
  d: path("m15 7 3 -3");
}

.hlr5flbgq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 7 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jmg_1z5qz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 6v14h10V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jvpl-4ewk {
  d: path("M15 10c4 0 4 6 0 6");
}

.lymn1951z {
  d: path("M6 12h4");
}

.m_lxwabcp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qruk0ip3j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 10c4 0 4 6 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rsteb5bse {
  d: path("M5 6v14h10V6");
}

.twn25-b-k {
  d: path("M6 16h4");
}

</style>
