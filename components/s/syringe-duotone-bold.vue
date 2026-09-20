<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g1-xv0h1s"/><path class="rq8-ufbbm"/><path class="jcehvlm7j"/><path class="tb-3q2ztn"/><path class="fn-c3ibgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:syringe-duotone-bold" /></template>
<style>
.fn-c3ibgj {
  d: path("m2.5 18.5 3 3");
}

.g1-xv0h1s {
  fill: currentColor;
  d: path("m6 15 8 -8 3 3 -8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jcehvlm7j {
  d: path("M15.5 8.5 20 4");
}

.rq8-ufbbm {
  d: path("m6 15 8 -8 3 3 -8 8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tb-3q2ztn {
  d: path("M7.5 16.5 4 20");
}

</style>
