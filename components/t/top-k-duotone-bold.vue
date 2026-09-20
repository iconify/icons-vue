<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="l9rn57bsk"/><path class="wsc8jcb1j"/><path class="j-oq7nbpn"/><path class="kxi7lgtij"/><path class="xgrfb-bqu"/><path class="r4xjkv11f"/><path class="n-7t0yb1r"/><path class="ukjt4fb6s"/><path class="yvi-t83_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:top-k-duotone-bold" /></template>
<style>
.j-oq7nbpn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kxi7lgtij {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9rn57bsk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.r4xjkv11f {
  d: path("M3 10h15");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ukjt4fb6s {
  d: path("M3 17h12");
}

.wsc8jcb1j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.yvi-t83_e {
  d: path("M3 21h9");
}

</style>
