<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="naa67qbfw"/><path class="l4a5a5bci"/><path class="f8e_ateex"/><path class="ppivcbbzp"/><path class="t87ohzbeq"/><path class="p8kjos25u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wait-event-duotone-bold" /></template>
<style>
.f8e_ateex {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 6 -4.5 4.5H17L12.5 15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l4a5a5bci {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.naa67qbfw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p8kjos25u {
  d: path("m19 6 -4.5 4.5H17L12.5 15");
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t87ohzbeq {
  d: path("M9 4v16");
}

</style>
