<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="li5ua4t9f"/><path class="v79iaqbup"/><path class="zsbobuxbe"/><path class="qbytwpbmn"/><path class="k3acnebvl"/><path class="q0_0mgbuo"/><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="o162teb3v"/><path class="cr8isx4cy"/><path class="jzkjbccbo"/><path class="e2nq-yvbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:umbrella-duotone-bold" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.cr8isx4cy {
  d: path("M15 12a3 3 0 0 1 -6 0");
}

.e2nq-yvbg {
  d: path("M12 15v6");
}

.jzkjbccbo {
  d: path("M21 12a3 3 0 0 1 -6 0");
}

.k3acnebvl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 12a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.li5ua4t9f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o162teb3v {
  d: path("M9 12a3 3 0 0 1 -6 0");
}

.q0_0mgbuo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 15v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qbytwpbmn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 12a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.v79iaqbup {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zsbobuxbe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
