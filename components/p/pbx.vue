<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGaGWm22hr)" class="p4anq1kxf"/><path fill="url(#SVGPpJYXc6x)" class="x-2dq0beb"/><path fill="url(#SVGtv6jpc9S)" class="k-r69acmm"/><path fill="url(#SVGwRJvKest)" class="xzjkm1bab"/><defs><linearGradient id="SVGaGWm22hr" x1="11.24" x2="16.614" y1="12.677" y2="8.187" gradientUnits="userSpaceOnUse"><stop class="cwmfu3bnu"/><stop offset="1" class="mphrhkbdr"/></linearGradient><linearGradient id="SVGPpJYXc6x" x1="9.439" x2="14.077" y1="17.35" y2="12.303" gradientUnits="userSpaceOnUse"><stop class="ekxjpq__s"/><stop offset="1" class="afwsridnq"/></linearGradient><linearGradient id="SVGtv6jpc9S" x1="7.793" x2="11.087" y1="20.991" y2="8.304" gradientUnits="userSpaceOnUse"><stop class="lqu9vjbew"/><stop offset=".98" class="b-3tgp79v"/></linearGradient><linearGradient id="SVGwRJvKest" x1="16.87" x2="15.488" y1="4.067" y2="5.965" gradientUnits="userSpaceOnUse"><stop class="d45h1qbgf"/><stop offset=".94" class="qc04mtb1i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pbx" /></template>
<style>
.afwsridnq {
  stop-color: var(--svg-color--9665fb, #9665fb);
}

.b-3tgp79v {
  stop-color: var(--svg-color--2880fa, #2880fa);
}

.cwmfu3bnu {
  stop-color: var(--svg-color--0080ee, #0080ee);
}

.d45h1qbgf {
  stop-color: var(--svg-color--00e5cc, #00e5cc);
}

.ekxjpq__s {
  stop-color: var(--svg-color--725bff, #725bff);
}

.ft5dv1b6b {
  fill: none;
}

.k-r69acmm {
  d: path("M3.584 9.751v8.364c0 2.136 2.177 3.53 4.028 2.583l.61-.313c3.018-1.567 2.704-6.124-.494-7.232c-2.292-.778-4.144-1.3-4.144-3.402");
}

.lqu9vjbew {
  stop-color: var(--svg-color--3c31d6, #3c31d6);
}

.mphrhkbdr {
  stop-color: var(--svg-color--01c5f6, #01c5f6);
}

.p4anq1kxf {
  d: path("M13.944 15.792H3.584V7.997C3.584 5.235 5.848 3 8.645 3h5.3c3.569.006 6.471 2.867 6.471 6.396s-2.902 6.396-6.472 6.396");
}

.qc04mtb1i {
  stop-color: var(--svg-color--10dcc6, #10dcc6);
}

.x-2dq0beb {
  d: path("M8.761 8.119c-3.169-1.567-3.424-3.134-3.146-4.12a4.97 4.97 0 0 0-2.031 4.004v7.934h10.36c1.527 0 2.926-.673 4.023-1.538c-.54-3.784-4.876-4.144-9.206-6.28");
}

.xzjkm1bab {
  d: path("M9.423 3.005c.754.83 2.356 1.88 5.815 2.554a13.6 13.6 0 0 1 4.905 2.008a6.47 6.47 0 0 0-6.199-4.562z");
}

</style>
