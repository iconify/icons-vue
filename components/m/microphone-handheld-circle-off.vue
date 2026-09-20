<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><g transform="translate(3 3)" class="qepuaqbvx"><circle transform="rotate(38.27 11.663 5.118)" class="ankvxfc_w"/><path class="nyi1rb2hl"/><path class="zc46plbst"/><path class="zjzss41qa"/></g><path class="z70afl_me"/><path clip-rule="evenodd" class="ksag4bb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:microphone-handheld-circle-off" /></template>
<style>
.ankvxfc_w {
  cx: 11.663px;
  cy: 5.118px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ft5dv1b6b {
  fill: none;
}

.ksag4bb-q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.nyi1rb2hl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8.544 5.842l-4.562 6.59m7.703-4.112l-5.348 5.97m-2.355-1.858l2.355 1.858");
}

.qepuaqbvx {
  stroke: currentColor;
}

.z70afl_me {
  fill: currentColor;
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.zc46plbst {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.617 2.867l.821 1.25a5 5 0 0 0 2.483 1.959l1.407.507");
}

.zjzss41qa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.7 14s-1.034 1.328-1.158 2c-.144.774.135 1.287.514 1.586s1.211.388 1.993.299c2.134-.245 3.423-3.438 5.35-4.385c1.488-.73 1.385-.632 3-1c1.374-.313 2.699-.547 2.699-.547");
}

</style>
