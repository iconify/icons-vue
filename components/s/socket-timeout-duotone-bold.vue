<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tvw8ildel"/><path class="xuznnacny"/><path class="gvmyg7bww"/><path class="w7f0uyb3r"/><path class="nrzizubal"/><path class="iyj_k-bwo"/><path class="lsfr6dm2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:socket-timeout-duotone-bold" /></template>
<style>
.gvmyg7bww {
  d: path("M2 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.iyj_k-bwo {
  d: path("M12 11v4");
}

.lsfr6dm2p {
  d: path("M12 15h4");
}

.nrzizubal {
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tvw8ildel {
  fill: currentColor;
  d: path("M2 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w7f0uyb3r {
  d: path("M6 5h14");
}

.xuznnacny {
  fill: currentColor;
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
