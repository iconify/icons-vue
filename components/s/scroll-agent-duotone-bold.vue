<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t5t_2ibim"/><path class="xv-xt-6hy"/><path class="sahhn_sjy"/><path class="sxmnd_utl"/><path class="w1fvqnt0l"/><path class="gtsw5xviq"/><path class="nkj1px1_f"/><path class="cfv90ubkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scroll-agent-duotone-bold" /></template>
<style>
.cfv90ubkl {
  d: path("M14.5 16.5 17 19l2.5 -2.5");
}

.gtsw5xviq {
  d: path("M17 5v14");
}

.nkj1px1_f {
  d: path("M14.5 7.5 17 5l2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sahhn_sjy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 7.5 17 5l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sxmnd_utl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 16.5 17 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t5t_2ibim {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w1fvqnt0l {
  d: path("M9.69 8.37a4 4 0 1 1 -3.38 0");
}

.xv-xt-6hy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
