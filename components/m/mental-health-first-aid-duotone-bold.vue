<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n97oqcbgk"/><path class="e3z5t3b6e"/><path class="na0bn4bbh"/><path class="uzrj-lb1g"/><path class="pohupsbfv"/><path class="f99n1fbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mental-health-first-aid-duotone-bold" /></template>
<style>
.e3z5t3b6e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 4v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f99n1fbkg {
  d: path("M16 7h6");
}

.n97oqcbgk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 21v-3c-1.5 -1.5 -2 -4 -2 -6.5a6 6 0 0 1 12 -1c0 1.5 1.5 2 1.5 3s-1 1 -1.5 1V17a1.5 1.5 0 0 1 -1.5 1.5H11V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.na0bn4bbh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pohupsbfv {
  d: path("M19 4v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uzrj-lb1g {
  d: path("M5 21v-3c-1.5 -1.5 -2 -4 -2 -6.5a6 6 0 0 1 12 -1c0 1.5 1.5 2 1.5 3s-1 1 -1.5 1V17a1.5 1.5 0 0 1 -1.5 1.5H11V21");
}

</style>
