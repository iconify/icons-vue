<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pk4yg3b6a"/><path class="jyrgo9c1z"/><path class="if6p90a7n"/><path class="ujr3us5qo"/><path class="xip8g_bzw"/><path class="rsteb5bse"/><path class="did41pbsp"/><path class="jvpl-4ewk"/><path class="lymn1951z"/><path class="twn25-b-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:measuring-jug-duotone-bold" /></template>
<style>
.did41pbsp {
  d: path("m15 7 3 -3");
}

.if6p90a7n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 10c4 0 4 6 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jvpl-4ewk {
  d: path("M15 10c4 0 4 6 0 6");
}

.jyrgo9c1z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 7 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lymn1951z {
  d: path("M6 12h4");
}

.pk4yg3b6a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 6v14h10V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rsteb5bse {
  d: path("M5 6v14h10V6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.twn25-b-k {
  d: path("M6 16h4");
}

.ujr3us5qo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xip8g_bzw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
