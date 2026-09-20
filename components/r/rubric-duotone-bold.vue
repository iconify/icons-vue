<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wvd8g1bvl"/><path class="lypr0rbtj"/><path class="dkassww8z"/><path class="i5tmmsb7a"/><path class="dm_ar8wjk"/><path class="b5p141rkx"/><path class="u9jggobpf"/><path class="cre86eeda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rubric-duotone-bold" /></template>
<style>
.b5p141rkx {
  d: path("M11 7.5h10");
}

.cre86eeda {
  d: path("M11 15.5h10");
}

.dkassww8z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 15 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dm_ar8wjk {
  d: path("m3 7 2 2 3 -3");
}

.i5tmmsb7a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 15.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lypr0rbtj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 7.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u9jggobpf {
  d: path("m3 15 2 2 3 -3");
}

.wvd8g1bvl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 7 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
