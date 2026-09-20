<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="siptj7bkm"/><path class="ysqks-b_k"/><path class="gk4de-b1j"/><path class="tr_jskylo"/><path class="ftrg70bds"/><path class="yih0nfb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:min-p-duotone-bold" /></template>
<style>
.ftrg70bds {
  d: path("M17 11v6");
}

.gk4de-b1j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.siptj7bkm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tr_jskylo {
  d: path("M7 5v12");
}

.yih0nfb7c {
  d: path("M3 14h18");
}

.ysqks-b_k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
