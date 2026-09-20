<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h68oqyb7w"/><path class="qtnzvq5nm"/><path class="s89cttbmk"/><path class="zyplbtn7l"/><path class="o--b0kbyk"/><path class="km05dlbsw"/><path class="c7dgfu7wx"/><path class="lgyhdeb-s"/><path class="j1kezkxcy"/><path class="ezp0d4btt"/><path class="gnit4mb6c"/><path class="lkpe2ldcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recursive-split-duotone-bold" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.ezp0d4btt {
  d: path("M2 16h3");
}

.gnit4mb6c {
  d: path("M7.5 16h3");
}

.h68oqyb7w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j1kezkxcy {
  d: path("M13.5 10H22");
}

.km05dlbsw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 16H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lgyhdeb-s {
  d: path("M2 10h8.5");
}

.lkpe2ldcq {
  d: path("M13.5 16H22");
}

.o--b0kbyk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qtnzvq5nm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 10h8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s89cttbmk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 10H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zyplbtn7l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
