<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="venoiz-zq"/><path class="jllohdbyn"/><path class="js0mhwyps"/><path class="qye9c0bkv"/><path class="vspm3ybjo"/><path class="qcxa0jb0g"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="odwdycbcr"/><path class="f-6kshnwt"/><path class="g7e-mbajx"/><path class="k7llgzrde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pet-cover-duotone-bold" /></template>
<style>
.a3eibhdgt {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

.f-6kshnwt {
  d: path("M11 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.g7e-mbajx {
  d: path("M15 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jllohdbyn {
  fill: currentColor;
  d: path("M11 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.js0mhwyps {
  fill: currentColor;
  d: path("M15 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k7llgzrde {
  d: path("M10 18.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.odwdycbcr {
  d: path("M7 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qcxa0jb0g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qye9c0bkv {
  fill: currentColor;
  d: path("M10 18.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.venoiz-zq {
  fill: currentColor;
  d: path("M7 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vspm3ybjo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z26gfvqcs {
  d: path("M4.5 9.5h15");
}

</style>
