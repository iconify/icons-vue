<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cc-oufnuo"/><path class="iy7yjsbzg"/><path class="rsu8hn7ln"/><path class="zhdz_msdd"/><path class="lp-5xmbze"/><path class="hplfm9bcc"/><path class="ils7yp4cg"/><path class="z0j9wnbwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-group-duotone-thin" /></template>
<style>
.cc-oufnuo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16V9l2 -2h4l2 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hplfm9bcc {
  d: path("M14 16V9l2 -2h4l2 2v7");
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.iy7yjsbzg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 16V9l2 -2h4l2 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lp-5xmbze {
  d: path("M2 16V9l2 -2h4l2 2v7");
}

.rsu8hn7ln {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z0j9wnbwo {
  d: path("M4 19.5h16");
}

.zhdz_msdd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 19.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
