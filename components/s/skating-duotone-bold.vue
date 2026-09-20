<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f2srn7b1n"/><path class="d4v3t3bns"/><path class="i0a2sm0mq"/><path class="w_zg9ublq"/><path class="uy5j3ks5u"/><path class="ok9ioqb8x"/><path class="pl-e7wb3s"/><path class="zuzyjabxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skating-duotone-bold" /></template>
<style>
.d4v3t3bns {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f2srn7b1n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 4v10h12v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i0a2sm0mq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.pl-e7wb3s {
  d: path("M6 14v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uy5j3ks5u {
  d: path("M6 4v10h12v-3");
}

.w_zg9ublq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuzyjabxh {
  d: path("M18 14v3");
}

</style>
