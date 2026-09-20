<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jz_46m_po"/><path class="vhh_tkp1r"/><path class="e3chl1vpv"/><path class="den3yubku"/><path class="t9xzqgb4s"/><path class="j3gawiblw"/><path class="bzbbywbmr"/><path class="fcs95kbsq"/><path class="w3gs3owfd"/><circle class="ndy1wwbfy"/><circle class="u6cfmt8wr"/><path class="wxxepkbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:school" /></template>
<style>
.bzbbywbmr {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M6 18h16v4H6zm0 6h16v4H6zm0 6h16v4H6z");
}

.den3yubku {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M28 17h2v18h-2z");
}

.e3chl1vpv {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M2 24h32v4H2zm0-6h32v4H2zm0 12h32v4H2z");
}

.fcs95kbsq {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M10 7h2v29h-2zm6 0h2v29h-2z");
}

.j3gawiblw {
  fill: var(--svg-color--808285, #808285);
  d: path("M22 0H6a2 2 0 0 0-2 2h20a2 2 0 0 0-2-2");
}

.jz_46m_po {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 34a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V15a2 2 0 0 1 2-2h32a2 2 0 0 1 2 2z");
}

.ndy1wwbfy {
  cx: 14px;
  cy: 9px;
  r: 6px;
  fill: var(--svg-color--a7a9ac, #a7a9ac);
}

.t9xzqgb4s {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M22 0H6a2 2 0 0 0-2 2v34h20V2a2 2 0 0 0-2-2");
}

.u6cfmt8wr {
  cx: 14px;
  cy: 9px;
  r: 4px;
  fill: var(--svg-color--e6e7e8, #e6e7e8);
}

.vhh_tkp1r {
  fill: var(--svg-color--6d6e71, #6d6e71);
  d: path("M34 13H2a2 2 0 0 0-2 2h36a2 2 0 0 0-2-2");
}

.w3gs3owfd {
  fill: var(--svg-color--269, #269);
  d: path("M12 30h4v6h-4z");
}

.wxxepkbva {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M17 10h-3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0v4h2a1 1 0 0 1 0 2");
}

</style>
