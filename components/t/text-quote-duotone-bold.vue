<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w7d8ui3is"/><path class="rvse0kbol"/><path class="wsc8jcb1j"/><path class="a97ht-z9f"/><path class="lnxt6xb6t"/><path class="dxrv6e9dn"/><path class="n-7t0yb1r"/><path class="ecph9tq5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-quote-duotone-bold" /></template>
<style>
.a97ht-z9f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dxrv6e9dn {
  d: path("M7 5v3h2.5");
}

.ecph9tq5i {
  d: path("M3 18h12");
}

.lnxt6xb6t {
  d: path("M3 5v3h2.5");
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.rvse0kbol {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 5v3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w7d8ui3is {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5v3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wsc8jcb1j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
