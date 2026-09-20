<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="yf_oz7mlk"/><path class="qqxvfgbxr"/><path class="upsyopbyx"/><path class="fqu8dpbxs"/><circle class="qpyz1k65m"/><path class="ub_2gwbhi"/><g class="n1mjunbsu"><path class="os6scfvqc"/><path class="xg8rqzbro"/></g><path class="u-t22mbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:no-mobile-phones" /></template>
<style>
.fqu8dpbxs {
  fill: var(--svg-color--fff, #fff);
  d: path("M71.75 24.64H58.07c-.7 0-1.27-.57-1.27-1.28c0-.7.58-1.28 1.27-1.28h13.68c.71 0 1.28.58 1.28 1.28c0 .71-.57 1.28-1.28 1.28");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.os6scfvqc {
  d: path("M53.21 97.14v.53l-1.14-.84l1.14-.84v.52h.67c1.28 0 2.12.38 2.12 1.49c0 1.12-.83 1.49-2.12 1.49H52.4v-.62h1.48c1.09 0 1.49-.24 1.49-.88c0-.63-.39-.87-1.49-.87h-.67zm13.88 2.15h-4.3v-2.17l2.16-.91l2.14.91zm-3.67-.62h3.05v-1.13l-1.52-.65l-1.53.65zm13.88.62h-3.59v-2.28h3.59zm-2.97-.62h2.35v-1.03h-2.35z");
}

.qpyz1k65m {
  cx: 79.8px;
  cy: 23.44px;
  r: 1.49px;
  fill: var(--svg-color--fff, #fff);
}

.qqxvfgbxr {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M64 128C28.71 128 0 99.29 0 64S28.71 0 64 0s64 28.71 64 64s-28.71 64-64 64m0-117.11c-29.29 0-53.11 23.83-53.11 53.11c0 29.29 23.83 53.11 53.11 53.11S117.11 93.29 117.11 64S93.29 10.89 64 10.89");
}

.u-t22mbpk {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M111.73 102.59L103.3 111L17 25.27l8.43-8.41z");
}

.ub_2gwbhi {
  fill: var(--svg-color--fff, #fff);
  d: path("M47 33h36v60H47z");
}

.upsyopbyx {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M83.22 20.33C80.05 18.91 70.78 18 64.91 18s-15.15.91-18.32 2.33c-3.1 1.4-4.35 4.14-4.35 6.74v72.88c0 2.59 1.25 5.34 4.35 6.73c3.17 1.42 12.45 2.33 18.32 2.33s15.14-.9 18.31-2.33c3.11-1.39 4.36-4.14 4.36-6.73V27.06c0-2.59-1.25-5.33-4.36-6.73");
}

.xg8rqzbro {
  d: path("M78.32 98.01h-.62v-1.34h-2.66v-.62h3.28z");
}

.yf_oz7mlk {
  cx: 63.3px;
  cy: 64.7px;
  r: 61.69px;
  fill: var(--svg-color--fff, #fff);
}

</style>
