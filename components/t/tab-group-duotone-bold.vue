<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="obz6mfb4b"/><path class="fr8xi54tu"/><path class="grt7vrw-d"/><path class="zw66s8b1o"/><path class="lp-5xmbze"/><path class="hplfm9bcc"/><path class="ils7yp4cg"/><path class="z0j9wnbwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-group-duotone-bold" /></template>
<style>
.fr8xi54tu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 16V9l2 -2h4l2 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.grt7vrw-d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hplfm9bcc {
  d: path("M14 16V9l2 -2h4l2 2v7");
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.lp-5xmbze {
  d: path("M2 16V9l2 -2h4l2 2v7");
}

.obz6mfb4b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16V9l2 -2h4l2 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z0j9wnbwo {
  d: path("M4 19.5h16");
}

.zw66s8b1o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 19.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
