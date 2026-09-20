<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u5-gj6qse"/><path class="k-awjwr9r"/><path class="tmfei69qh"/><path class="zh6q_cf_u"/><path class="rwge04jxw"/><path class="g7akhoeoj"/><path class="wlp3ibbib"/><path class="qrqk-5btd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wardrobe-sort-duotone-bold" /></template>
<style>
.g7akhoeoj {
  d: path("m6 13 6 -6 6 6");
}

.k-awjwr9r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrqk-5btd {
  d: path("m9 17 3 3 3 -3");
}

.rwge04jxw {
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tmfei69qh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u5-gj6qse {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlp3ibbib {
  d: path("M6 13h12");
}

.zh6q_cf_u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
