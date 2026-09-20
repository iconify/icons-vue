<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqn8oeb4o"/><path class="hpm6v1-ys"/><path class="cs9f_sbcc"/><path class="b94_zib6w"/><path class="z3govm5hv"/><path class="mg7aqnbsf"/><path class="jkuojibnm"/><path class="h7bcztycq"/><path class="bhl_zu55p"/><path class="p9jmvgbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spacer-duotone-bold" /></template>
<style>
.aqn8oeb4o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b94_zib6w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 10.5 12 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bhl_zu55p {
  d: path("M9.5 10.5 12 8l2.5 2.5");
}

.cs9f_sbcc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7bcztycq {
  d: path("M12 8v8");
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.p9jmvgbqq {
  d: path("M9.5 13.5 12 16l2.5 -2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z3govm5hv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 13.5 12 16l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
