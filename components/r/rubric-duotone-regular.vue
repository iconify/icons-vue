<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lau918bij"/><path class="mmhk4dbsl"/><path class="hliogkb-y"/><path class="sgktqbc9n"/><path class="dm_ar8wjk"/><path class="b5p141rkx"/><path class="u9jggobpf"/><path class="cre86eeda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rubric-duotone-regular" /></template>
<style>
.b5p141rkx {
  d: path("M11 7.5h10");
}

.cre86eeda {
  d: path("M11 15.5h10");
}

.dm_ar8wjk {
  d: path("m3 7 2 2 3 -3");
}

.hliogkb-y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 15 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lau918bij {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 7 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mmhk4dbsl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 7.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sgktqbc9n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 15.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u9jggobpf {
  d: path("m3 15 2 2 3 -3");
}

</style>
