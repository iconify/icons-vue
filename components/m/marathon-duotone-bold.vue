<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o_11v4jkg"/><path class="y54kzvujh"/><path class="yry22nrne"/><path class="d5eh_ybsj"/><path class="kkm03rbxe"/><path class="uqqniu6bc"/><path class="j2-drqnzq"/><path class="lp-jzobeh"/><path class="lvrweqtce"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:marathon-duotone-bold" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.d5eh_ybsj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 15 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j2-drqnzq {
  d: path("m13 7 -4 4 4 4");
}

.kkm03rbxe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lp-jzobeh {
  d: path("M9 11H5");
}

.lvrweqtce {
  d: path("m13 15 4 4");
}

.o_11v4jkg {
  fill: currentColor;
  d: path("M11 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uqqniu6bc {
  d: path("M11 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.y54kzvujh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 7 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yry22nrne {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 11H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
