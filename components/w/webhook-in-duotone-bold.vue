<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mypzt1bhf"/><path class="dzaxh3b_q"/><path class="wc2iww91l"/><path class="pqnqi359s"/><path class="qw94a7xnn"/><path class="n0hr0gbrt"/><path class="jcxg2bbvb"/><path class="i50mf1njm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:webhook-in-duotone-bold" /></template>
<style>
.dzaxh3b_q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 6.8a6 6 0 1 1 0 10.4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i50mf1njm {
  d: path("m7 9 3 3 -3 3");
}

.jcxg2bbvb {
  d: path("M2 12h8");
}

.mypzt1bhf {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n0hr0gbrt {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.pqnqi359s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qw94a7xnn {
  d: path("M13 6.8a6 6 0 1 1 0 10.4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wc2iww91l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
