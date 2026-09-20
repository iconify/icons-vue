<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sutd9hkuk"/><path class="q9qkwgbhj"/><path class="z-f5p056k"/><path class="ai1uaccli"/><path class="zstw_8bqr"/><path class="h-upazbnx"/><path class="g2hfxvq5b"/><path class="rp5jumb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:moving-box-duotone-regular" /></template>
<style>
.ai1uaccli {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g2hfxvq5b {
  d: path("m20 8 -3 -3");
}

.h-upazbnx {
  d: path("m4 8 3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q9qkwgbhj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 8 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rp5jumb9f {
  d: path("M12 8v11");
}

.sutd9hkuk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8v11h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z-f5p056k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20 8 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zstw_8bqr {
  d: path("M4 8v11h16V8");
}

</style>
