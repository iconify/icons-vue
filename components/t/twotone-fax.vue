<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmnihccsa"/><path class="dymu-6bfq"/><circle class="alqc54g4m"/><circle class="c12g01cey"/><circle class="tprbgvb_u"/><circle class="c9gbovbnk"/><path class="ju148-33l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-fax" /></template>
<style>
.alqc54g4m {
  cx: 15px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.c12g01cey {
  cx: 18px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.c9gbovbnk {
  cx: 18px;
  cy: 16px;
  r: 1px;
  fill: currentColor;
}

.dymu-6bfq {
  fill: currentColor;
  d: path("M19 9h-1V4H8v5h-.78C6.67 8.39 5.89 8 5 8c-1.66 0-3 1.34-3 3v7c0 1.66 1.34 3 3 3c.89 0 1.67-.39 2.22-1H22v-8c0-1.66-1.34-3-3-3M6 18c0 .55-.45 1-1 1s-1-.45-1-1v-7c0-.55.45-1 1-1s1 .45 1 1zm4-12h6v3h-6zm10 12H8v-7h11c.55 0 1 .45 1 1z");
}

.ju148-33l {
  fill: currentColor;
  d: path("M9 12h4v5H9z");
}

.tprbgvb_u {
  cx: 15px;
  cy: 16px;
  r: 1px;
  fill: currentColor;
}

.xmnihccsa {
  fill: currentColor;
  d: path("M5 10c-.55 0-1 .45-1 1v7c0 .55.45 1 1 1s1-.45 1-1v-7c0-.55-.45-1-1-1m5-4h6v3h-6zm9 5H8v7h12v-6c0-.55-.45-1-1-1m-6 6H9v-5h4zm2 0c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m0-3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m3 3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m0-3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
