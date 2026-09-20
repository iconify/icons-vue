<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="era6l482e"/><path class="hqf0gm-hw"/><path class="m8ik1r-gw"/><path class="jt3ip0bnx"/><path class="eqs3qacps"/><path class="h68oqyb7w"/><path class="f1psbbcsw"/><path class="kdl_ri28b"/><path class="lkivjibuo"/><path class="yzvng5w1c"/><path class="e-0451fwt"/><path class="c7dgfu7wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:percentile-duotone-bold" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.e-0451fwt {
  d: path("M20 16v4");
}

.eqs3qacps {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 16v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.era6l482e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 15v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f1psbbcsw {
  d: path("M4 15v5");
}

.h68oqyb7w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hqf0gm-hw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jt3ip0bnx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kdl_ri28b {
  d: path("M8 11v9");
}

.lkivjibuo {
  d: path("M12 13v7");
}

.m8ik1r-gw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yzvng5w1c {
  d: path("M16 7v13");
}

</style>
