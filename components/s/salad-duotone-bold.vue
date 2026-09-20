<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y1nfwg_iv"/><path class="qv3s7etjk"/><path class="i5ho0k7me"/><path class="eyi8t4bxj"/><path class="k187sabpz"/><path class="kpavcn10r"/><path class="n5cv_rbxc"/><path class="o7aygz06s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:salad-duotone-bold" /></template>
<style>
.eyi8t4bxj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m11 11 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i5ho0k7me {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 11 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k187sabpz {
  d: path("M2 11h20");
}

.kpavcn10r {
  d: path("M21 11a9 9 0 0 1 -18 0");
}

.n5cv_rbxc {
  d: path("m5 11 4 -4 4 4");
}

.o7aygz06s {
  d: path("m11 11 4 -4 4 4");
}

.qv3s7etjk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 11a9 9 0 0 1 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y1nfwg_iv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 11h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
