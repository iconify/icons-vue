<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="racigruuj"/><path class="zsmb_xb5b"/><path class="i89qw1_fx"/><path class="re-gar4bf"/><path class="xaxtk6cud"/><path class="kj4zxsc0v"/><path class="ymfnpaceh"/><path class="c4g909b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sync-duotone-bold" /></template>
<style>
.c4g909b2h {
  d: path("m12 17 -2.5 2.5L12 22");
}

.i89qw1_fx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 2 2.5 2.5L12 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kj4zxsc0v {
  d: path("M9.5 19.5H6a3 3 0 0 1 -3 -3v-9a3 3 0 0 1 3 -3h3.5");
}

.racigruuj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 4.5H18a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3h-3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.re-gar4bf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 17 -2.5 2.5L12 22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xaxtk6cud {
  d: path("M14.5 4.5H18a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3h-3.5");
}

.ymfnpaceh {
  d: path("m12 2 2.5 2.5L12 7");
}

.zsmb_xb5b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 19.5H6a3 3 0 0 1 -3 -3v-9a3 3 0 0 1 3 -3h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
