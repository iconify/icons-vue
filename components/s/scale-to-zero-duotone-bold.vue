<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxjvqtiry"/><path class="pfbcu141c"/><path class="qe97cg-lx"/><path class="f_0n8xbzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scale-to-zero-duotone-bold" /></template>
<style>
.f_0n8xbzv {
  d: path("m5 7 6 6 8 8");
}

.pfbcu141c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 7 6 6 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yxjvqtiry {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
