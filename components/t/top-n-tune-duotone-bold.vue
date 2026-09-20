<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wg39mccfx"/><path class="zrf1-2b0r"/><path class="r0hqtnb_b"/><path class="cshpr1b1a"/><path class="xpx81g6sq"/><path class="zrmtxyafv"/><path class="u07qp3bhr"/><path class="kiz2lrbtx"/><path class="y_or9-s0p"/><path class="yqy8x4bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:top-n-tune-duotone-bold" /></template>
<style>
.cshpr1b1a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kiz2lrbtx {
  d: path("M8 14h12");
}

.r0hqtnb_b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u07qp3bhr {
  d: path("M8 9h12");
}

.wg39mccfx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xpx81g6sq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 2H3v9h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y_or9-s0p {
  d: path("M8 19h12");
}

.yqy8x4bvc {
  d: path("M5.5 2H3v9h2.5");
}

.zrf1-2b0r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zrmtxyafv {
  d: path("M8 4h12");
}

</style>
