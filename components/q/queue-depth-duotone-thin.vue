<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yck3zxb2b"/><path class="wpnd__b2z"/><path class="tcvmtxbda"/><path class="ftka6y45f"/><path class="l-8pkdhvs"/><path class="xhwe0sbyf"/><path class="ze3hawb4v"/><path class="vdq8lyksd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:queue-depth-duotone-thin" /></template>
<style>
.ftka6y45f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-8pkdhvs {
  d: path("M6.5 4H4v16h2.5");
}

.tcvmtxbda {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdq8lyksd {
  d: path("M18 12v6");
}

.wpnd__b2z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xhwe0sbyf {
  d: path("M10 9v9");
}

.yck3zxb2b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.5 4H4v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ze3hawb4v {
  d: path("M14 6v12");
}

</style>
