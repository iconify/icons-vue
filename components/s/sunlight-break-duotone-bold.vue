<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dxj-8f9ba"/><path class="erzw1mb7a"/><path class="dxyj_mbqg"/><path class="trd9hx4dy"/><path class="kbt5_mz7x"/><path class="kt4kzrb6r"/><path class="nvn647bwx"/><path class="p7tekpb9x"/><path class="tea8p3bbk"/><path class="ennto9b9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunlight-break-duotone-bold" /></template>
<style>
.dxj-8f9ba {
  fill: currentColor;
  d: path("M10 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dxyj_mbqg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 8h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ennto9b9x {
  d: path("M16 16h5");
}

.erzw1mb7a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 21V4h8v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kbt5_mz7x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 16h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kt4kzrb6r {
  d: path("M5 21V4h8v17");
}

.nvn647bwx {
  d: path("M10 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p7tekpb9x {
  d: path("M16 8h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tea8p3bbk {
  d: path("M16 12h5");
}

.trd9hx4dy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
