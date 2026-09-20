<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f6q7r5bds"/><path class="krwm4ebpd"/><path class="ezo88ccul"/><path class="w2qoutbxx"/><path class="mw0thacpt"/><path class="ew7y79byi"/><path class="huj3g_bus"/><path class="xob7qnbfo"/><path class="nycbsrkgh"/><path class="wwbyt5bkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:music-note-duotone-regular" /></template>
<style>
.ew7y79byi {
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ezo88ccul {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 17V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f6q7r5bds {
  fill: currentColor;
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.huj3g_bus {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.krwm4ebpd {
  fill: currentColor;
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mw0thacpt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nycbsrkgh {
  d: path("M17 17V5");
}

.w2qoutbxx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 17V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wwbyt5bkd {
  d: path("M9 5h8");
}

.xob7qnbfo {
  d: path("M9 17V5");
}

</style>
