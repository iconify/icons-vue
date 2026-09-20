<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eff5yibna"/><path class="q60od4b5c"/><path class="sk-cs8ujn"/><path class="xd6cehb8s"/><path class="tcvietbrx"/><path class="jkde9pg-v"/><path class="pq9ly31-r"/><path class="wgmj3x5ib"/><path class="h_yag6b0i"/><path class="zc1w0xe2t"/><path class="qv5w5objz"/><path class="c7u43zhgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pose-duotone-bold" /></template>
<style>
.c7u43zhgq {
  d: path("m12 14 5 5");
}

.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h_yag6b0i {
  d: path("m12 8 -5 5");
}

.jkde9pg-v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 14 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.q60od4b5c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qv5w5objz {
  d: path("m12 14 -5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sk-cs8ujn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 8 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tcvietbrx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 14 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wgmj3x5ib {
  d: path("M12 6v8");
}

.xd6cehb8s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 8 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zc1w0xe2t {
  d: path("m12 8 5 5");
}

</style>
