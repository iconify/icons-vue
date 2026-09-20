<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><path class="hnbni-bzp"/><rect class="n_uko89cm"/><circle class="t4xsmibtj"/><path class="tg7r0ibct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rhvoice" /></template>
<style>
.hnbni-bzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 27.54v-6.703h2.195c1.24 0 2.247 1.008 2.247 2.251s-1.006 2.252-2.247 2.252H8m2.195 0l2.194 2.199m1.678-6.702v6.704m4.442-6.704v6.704m-4.442-3.365h4.442m6.036-3.339l-2.221 6.704l-2.221-6.704");
}

.n_uko89cm {
  width: 3.352px;
  height: 4.441px;
  x: 25.109px;
  y: 23.099px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.676px;
  ry: 1.676px;
}

.t4xsmibtj {
  cx: 30.209px;
  cy: 21.046px;
  r: 0.75px;
  fill: currentColor;
}

.tg7r0ibct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.209 23.099v4.442m9.571-.846a1.676 1.676 0 0 1-3.132-.83v-1.09a1.676 1.676 0 0 1 3.352 0v.545h-3.352m-1.574 1.376a1.676 1.676 0 0 1-3.131-.832v-1.089a1.675 1.675 0 0 1 3.13-.835");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
