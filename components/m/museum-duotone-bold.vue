<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q2zf-bc9g"/><path class="h7t_rfzha"/><path class="fewd_qbim"/><path class="r1sj09b-f"/><path class="kkm03rbxe"/><path class="wlpa9-b1f"/><path class="aut8y9hmn"/><path class="k6x6uv-ap"/><path class="h2va4xb2x"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:museum-duotone-bold" /></template>
<style>
.aut8y9hmn {
  d: path("M7 12v7");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.fewd_qbim {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2va4xb2x {
  d: path("M17 11v8");
}

.h7t_rfzha {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6x6uv-ap {
  d: path("M12 11v8");
}

.kkm03rbxe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q2zf-bc9g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 11 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r1sj09b-f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wlpa9-b1f {
  d: path("m5 11 7 -7 7 7");
}

</style>
