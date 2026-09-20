<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vx9rskbcr"/><path class="siptj7bkm"/><path class="ixxv1jyxb"/><path class="a3ddw9bqs"/><path class="oyalg6pos"/><path class="xf07dvr8m"/><path class="tr_jskylo"/><path class="hxoe7gx5p"/><path class="e0001wg8c"/><path class="y_21nobec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:waterfall-duotone-bold" /></template>
<style>
.a3ddw9bqs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e0001wg8c {
  d: path("M17 5v12");
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.ixxv1jyxb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oyalg6pos {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.siptj7bkm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tr_jskylo {
  d: path("M7 5v12");
}

.vx9rskbcr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xf07dvr8m {
  d: path("M2 5h20");
}

.y_21nobec {
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
