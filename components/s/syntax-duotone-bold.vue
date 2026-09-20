<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dhgggtb3s"/><path class="mvc_pjbyz"/><path class="rv1mb2bps"/><path class="mufl12bgg"/><path class="zaau21ski"/><path class="vj8si9dha"/><path class="fa2e7y2tg"/><path class="wfg0vmbgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:syntax-duotone-bold" /></template>
<style>
.dhgggtb3s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4 4 8l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fa2e7y2tg {
  d: path("M4 17h8");
}

.mufl12bgg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 17h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mvc_pjbyz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 4 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rv1mb2bps {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vj8si9dha {
  d: path("m16 4 4 4 -4 4");
}

.wfg0vmbgy {
  d: path("M15 17h5");
}

.zaau21ski {
  d: path("M8 4 4 8l4 4");
}

</style>
