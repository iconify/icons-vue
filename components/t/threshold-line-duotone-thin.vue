<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="wmj0hybky"/><path class="yb8rosbvw"/><path class="oyhwljbnu"/><path class="mh1fpo6op"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="a5uqb5btg"/><path class="qn21uclav"/><path class="mcdduacou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:threshold-line-duotone-thin" /></template>
<style>
.a5uqb5btg {
  d: path("M9 14v4");
}

.e_6o-gbms {
  d: path("M6 10h13");
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcdduacou {
  d: path("M17 7v11");
}

.mh1fpo6op {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.oyhwljbnu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qn21uclav {
  d: path("M13 12v6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.wmj0hybky {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb8rosbvw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
