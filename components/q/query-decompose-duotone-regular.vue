<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="xg3yyebvz"/><path class="wdpreqbqj"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="d7edxnn1x"/><path class="s00zhtbiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:query-decompose-duotone-regular" /></template>
<style>
.d7edxnn1x {
  d: path("M5.5 10H8l2.5 -2.5H13");
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qa-jr78us {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s00zhtbiw {
  d: path("m8 10 2.5 2.5H13");
}

.vxtvt1e5w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wdpreqbqj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 10 2.5 2.5H13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xg3yyebvz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 10H8l2.5 -2.5H13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
