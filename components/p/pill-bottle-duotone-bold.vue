<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yerw84_9m"/><path class="t69363l7x"/><path class="q_br9pbky"/><path class="ptaeireto"/><path class="e8vupfb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pill-bottle-duotone-bold" /></template>
<style>
.e8vupfb9c {
  d: path("M9.5 14h5");
}

.ptaeireto {
  d: path("M12 11.5v5");
}

.q_br9pbky {
  d: path("M8 8V4h8v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t69363l7x {
  d: path("M6 8v13h12V8Z");
}

.yerw84_9m {
  fill: currentColor;
  d: path("M6 8v13h12V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
