<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mg9hj4bbp"/><path class="xv-xt-6hy"/><path class="swmt31b1p"/><path class="gtsw5xviq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skip-forward-duotone-bold" /></template>
<style>
.gtsw5xviq {
  d: path("M17 5v14");
}

.mg9hj4bbp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.swmt31b1p {
  d: path("m6 5 7 7 -7 7");
}

.xv-xt-6hy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
