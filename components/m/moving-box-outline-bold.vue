<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zstw_8bqr"/><path class="h-upazbnx"/><path class="g2hfxvq5b"/><path class="rp5jumb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:moving-box-outline-bold" /></template>
<style>
.g2hfxvq5b {
  d: path("m20 8 -3 -3");
}

.h-upazbnx {
  d: path("m4 8 3 -3");
}

.rp5jumb9f {
  d: path("M12 8v11");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zstw_8bqr {
  d: path("M4 8v11h16V8");
}

</style>
