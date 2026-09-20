<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="its1e1bwq"/><path class="tqe2jhbja"/><path class="z2lk9ryev"/><path class="ppivcbbzp"/><path class="t87ohzbeq"/><path class="p8kjos25u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wait-event-duotone-regular" /></template>
<style>
.its1e1bwq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8kjos25u {
  d: path("m19 6 -4.5 4.5H17L12.5 15");
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.t87ohzbeq {
  d: path("M9 4v16");
}

.tqe2jhbja {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z2lk9ryev {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 6 -4.5 4.5H17L12.5 15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
