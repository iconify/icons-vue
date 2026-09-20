<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qlqs7mbtz"/><path class="kfpn31m7n"/><path class="eawx7b1rq"/><path class="djy76tbah"/><path class="ttpxlcc5b"/><path class="wfmdw-bov"/><path class="jjxl5r6ig"/><path class="cmwdgpbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scheduler-k8s-duotone-bold" /></template>
<style>
.cmwdgpbrv {
  d: path("M2 17.5h20");
}

.djy76tbah {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 17.5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eawx7b1rq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 4 12 6.5 14.5 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jjxl5r6ig {
  d: path("M10 11.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kfpn31m7n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qlqs7mbtz {
  fill: currentColor;
  d: path("M10 11.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.ttpxlcc5b {
  d: path("M12 3v3.5");
}

.wfmdw-bov {
  d: path("M9.5 4 12 6.5 14.5 4");
}

</style>
