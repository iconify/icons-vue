<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="g55pkgb9q"/><path class="wnqh8n3mu"/><path class="fisu-v21f"/><path class="esnhr1wgb"/><path class="c3h6-1bwq"/><path class="xgrfb-bqu"/><path class="d8abqfbpc"/><path class="k0js09kko"/><path class="qouhnhnfp"/><path class="t40-rxb9c"/><path class="elwkggrsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-complete-duotone-bold" /></template>
<style>
.c3h6-1bwq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M22 13.5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d8abqfbpc {
  d: path("M3 11h18");
}

.elwkggrsn {
  d: path("M22 13.5v5");
}

.esnhr1wgb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 13.5 19 16l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fisu-v21f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g55pkgb9q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k0js09kko {
  d: path("M3 16h9");
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qouhnhnfp {
  d: path("M15 16h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t40-rxb9c {
  d: path("M16.5 13.5 19 16l-2.5 2.5");
}

.wnqh8n3mu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
