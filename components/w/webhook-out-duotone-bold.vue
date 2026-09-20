<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgscl2bdj"/><path class="by_v_6s1o"/><path class="d9o-_rb6e"/><path class="fb_qk2zpm"/><path class="vd_ltu4xs"/><path class="zirb-hbnv"/><path class="jlfl_ccwj"/><path class="wn519caci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:webhook-out-duotone-bold" /></template>
<style>
.by_v_6s1o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 6.8a6 6 0 0 1 0 10.4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d9o-_rb6e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fb_qk2zpm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jlfl_ccwj {
  d: path("M14 12h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vd_ltu4xs {
  d: path("M11 6.8a6 6 0 0 1 0 10.4");
}

.wn519caci {
  d: path("m19 9 3 3 -3 3");
}

.xgscl2bdj {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zirb-hbnv {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
