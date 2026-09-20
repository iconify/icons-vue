<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d1wv1pbpc"/><path class="bi4el8ygv"/><path class="uwx4n6b8m"/><path class="zlcluhetu"/><path class="w1fvqnt0l"/><path class="gtsw5xviq"/><path class="nkj1px1_f"/><path class="cfv90ubkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scroll-agent-duotone-thin" /></template>
<style>
.bi4el8ygv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cfv90ubkl {
  d: path("M14.5 16.5 17 19l2.5 -2.5");
}

.d1wv1pbpc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gtsw5xviq {
  d: path("M17 5v14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nkj1px1_f {
  d: path("M14.5 7.5 17 5l2.5 2.5");
}

.uwx4n6b8m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 7.5 17 5l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w1fvqnt0l {
  d: path("M9.69 8.37a4 4 0 1 1 -3.38 0");
}

.zlcluhetu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 16.5 17 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
