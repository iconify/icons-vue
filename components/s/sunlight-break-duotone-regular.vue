<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dxj-8f9ba"/><path class="dkmtdfb2a"/><path class="iiyv3nbiq"/><path class="zk8d0pb3d"/><path class="xfjzwobgh"/><path class="kt4kzrb6r"/><path class="nvn647bwx"/><path class="p7tekpb9x"/><path class="tea8p3bbk"/><path class="ennto9b9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunlight-break-duotone-regular" /></template>
<style>
.dkmtdfb2a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 21V4h8v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dxj-8f9ba {
  fill: currentColor;
  d: path("M10 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ennto9b9x {
  d: path("M16 16h5");
}

.iiyv3nbiq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 8h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kt4kzrb6r {
  d: path("M5 21V4h8v17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvn647bwx {
  d: path("M10 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p7tekpb9x {
  d: path("M16 8h5");
}

.tea8p3bbk {
  d: path("M16 12h5");
}

.xfjzwobgh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 16h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zk8d0pb3d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
