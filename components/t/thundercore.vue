<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGMHYekeZK)" class="t7srub4ck"/><defs><linearGradient id="SVGMHYekeZK" x1="10.772" x2="13.936" y1="6.715" y2="20.311" gradientUnits="userSpaceOnUse"><stop offset=".18" class="wvxzetb7r"/><stop offset=".23" class="po-x6pbfy"/><stop offset=".31" class="aucn-8m7b"/><stop offset=".4" class="q-_-sxlgr"/><stop offset=".51" class="sivfzgbzu"/><stop offset=".62" class="qjxt69obc"/><stop offset=".74" class="o_swsjoqm"/><stop offset=".78" class="wli72ud7c"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:thundercore" /></template>
<style>
.aucn-8m7b {
  stop-color: var(--svg-color--00e4d5, #00e4d5);
}

.ft5dv1b6b {
  fill: none;
}

.o_swsjoqm {
  stop-color: var(--svg-color--0016d5, #0016d5);
}

.po-x6pbfy {
  stop-color: var(--svg-color--00f8d5, #00f8d5);
}

.q-_-sxlgr {
  stop-color: var(--svg-color--00c3d5, #00c3d5);
}

.qjxt69obc {
  stop-color: var(--svg-color--005cd5, #005cd5);
}

.sivfzgbzu {
  stop-color: var(--svg-color--0096d5, #0096d5);
}

.t7srub4ck {
  d: path("M6.76 11.453a.4.4 0 0 0 .338.612h4.56a.191.191 0 0 1 .162.293l-4.474 7.164a.16.16 0 0 1-.225.05a9.01 9.01 0 0 1 4.592-16.571a.159.159 0 0 1 .137.242zm10.282-6.912a.16.16 0 0 0-.225.048l-4.406 7.059a.192.192 0 0 0 .162.292h4.56a.4.4 0 0 1 .337.612l-5.155 8.255a.125.125 0 0 0 .113.192A9.008 9.008 0 0 0 17.04 4.541z");
}

.wli72ud7c {
  stop-color: var(--svg-color--0000d5, #0000d5);
}

.wvxzetb7r {
  stop-color: var(--svg-color--00ffd5, #00ffd5);
}

</style>
