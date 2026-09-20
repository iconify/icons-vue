<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rlbrj1bkl"/><path class="u-pn1xbtk"/><path class="vwqgo5sgm"/><path class="xujn_cdhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:price-down-duotone-bold" /></template>
<style>
.rlbrj1bkl {
  fill: currentColor;
  d: path("M8 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-pn1xbtk {
  d: path("M8 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.vwqgo5sgm {
  d: path("M12 14v6.5");
}

.xujn_cdhr {
  d: path("m9.5 18 2.5 2.5 2.5 -2.5");
}

</style>
