<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p8iop6bwz"/><path class="vugti51pk"/><path class="ow_8zyeff"/><path class="jujxaqbqg"/><path class="q6rh9u55e"/><path class="v_a3lnirg"/><path class="lvtw3tv7j"/><path class="c-xj8zban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ski-run-duotone-regular" /></template>
<style>
.c-xj8zban {
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jujxaqbqg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 21 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lvtw3tv7j {
  d: path("m16 21 5 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ow_8zyeff {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21 18 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p8iop6bwz {
  fill: currentColor;
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q6rh9u55e {
  d: path("M3 18 15 6");
}

.v_a3lnirg {
  d: path("M6 21 18 9");
}

.vugti51pk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18 15 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
