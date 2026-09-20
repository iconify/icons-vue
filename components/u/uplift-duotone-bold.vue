<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7t_rfzha"/><path class="kln-5abxc"/><path class="tu8ll15ii"/><path class="k2a_yiwqn"/><path class="aut8y9hmn"/><path class="ow_ax0v9r"/><path class="du_3_4tit"/><path class="sgi0qkbzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:uplift-duotone-bold" /></template>
<style>
.aut8y9hmn {
  d: path("M7 12v7");
}

.du_3_4tit {
  d: path("M4 21.5h16");
}

.h7t_rfzha {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k2a_yiwqn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 10.5 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kln-5abxc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ow_ax0v9r {
  d: path("M15 6v13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sgi0qkbzh {
  d: path("m9 10.5 3 -3");
}

.tu8ll15ii {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
