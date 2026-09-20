<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vvigh05rm"/><path class="e7q5mxbif"/><path class="f9ep66zgp"/><path class="ve_xbsdkz"/><path class="e9dh58ngn"/><path class="m_7wrpotl"/><path class="ha1vlxxyu"/><path class="se99362hb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stethoscope-duotone-bold" /></template>
<style>
.e7q5mxbif {
  fill: currentColor;
  d: path("M17 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e9dh58ngn {
  d: path("M5 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.f9ep66zgp {
  fill: currentColor;
  d: path("M9 19a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ha1vlxxyu {
  d: path("M12 14v2.5");
}

.m_7wrpotl {
  d: path("M17 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.se99362hb {
  d: path("M9 19a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.ve_xbsdkz {
  d: path("M6 4v4a6 6 0 0 0 12 0V4");
}

.vvigh05rm {
  fill: currentColor;
  d: path("M5 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
