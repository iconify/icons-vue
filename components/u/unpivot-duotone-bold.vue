<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vdu_blb2q"/><path class="pmp70t7tc"/><path class="ox85y3b8d"/><path class="sm8yo0y2z"/><path class="gam3cw54g"/><path class="hpm6v1-ys"/><path class="j4m0w2b-t"/><path class="p3dq04btg"/><path class="i9hpnuf0x"/><path class="z0ud8rb7a"/><path class="ys-dg812g"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unpivot-duotone-bold" /></template>
<style>
.gam3cw54g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i9hpnuf0x {
  d: path("M18 2v5.5");
}

.j4m0w2b-t {
  d: path("M6 2v5.5");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.ox85y3b8d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p3dq04btg {
  d: path("M12 2v5.5");
}

.pmp70t7tc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sm8yo0y2z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 10.5 12 13l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdu_blb2q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

.z0ud8rb7a {
  d: path("M9.5 10.5 12 13l2.5 -2.5");
}

</style>
