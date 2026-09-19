<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9CVtyd)" class="hy4x1nb-j"/><path fill="url(#iQg3dLe)" class="hy4x1nb-j"/><path fill="url(#iarF6gB)" class="hy4x1nb-j"/><path fill="url(#iV83u2J)" class="hy4x1nb-j"/><path fill="url(#i6ih3Mc)" class="hy4x1nb-j"/><defs><radialGradient id="i9CVtyd" cx="0" cy="0" r="1" gradientTransform="rotate(130.168 9.831 9.886)scale(27.8086)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mabrieb0z"/><stop offset=".853" class="jmvw7t_mq"/></radialGradient><radialGradient id="iarF6gB" cx="0" cy="0" r="1" gradientTransform="matrix(-9.47663 8.74999 -8.07914 -8.75007 24.227 10.75)" gradientUnits="userSpaceOnUse"><stop class="hmyk92buh"/><stop offset="1" class="n_dafjabd"/></radialGradient><radialGradient id="iV83u2J" cx="0" cy="0" r="1" gradientTransform="matrix(-19.25 0 0 -20 20.04 16)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="t7rtk_4tu"/><stop offset=".951" class="m8wfk57ly"/></radialGradient><radialGradient id="i6ih3Mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 21 -23.3208 0 15.547 9)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="qxf2o531r"/><stop offset="1" class="c7y6gdfxm"/></radialGradient><linearGradient id="iQg3dLe" x1="15.547" x2="15.547" y1="2" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="o967e0bgk"/><stop offset="1" class="dv9lpnbkq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:purple-circle" /></template>
<style>
.c7y6gdfxm {
  stop-color: var(--svg-color--8352ca, #8352CA);
}

.dv9lpnbkq {
  stop-color: var(--svg-color--8171aa, #8171AA);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hmyk92buh {
  stop-color: var(--svg-color--a087d8, #A087D8);
}

.hy4x1nb-j {
  d: path("M29.547 16c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.jmvw7t_mq {
  stop-color: var(--svg-color--7047b7, #7047B7);
}

.m8wfk57ly {
  stop-color: var(--svg-color--afa6cb, #AFA6CB);
}

.mabrieb0z {
  stop-color: var(--svg-color--8971bd, #8971BD);
}

.n_dafjabd {
  stop-color: var(--svg-color--9879d7, #9879D7);
  stop-opacity: 0;
}

.o967e0bgk {
  stop-color: var(--svg-color--8171aa, #8171AA);
}

.qxf2o531r {
  stop-color: var(--svg-color--743ec3, #743EC3);
  stop-opacity: 0;
}

.t7rtk_4tu {
  stop-color: var(--svg-color--6e56a1, #6E56A1);
  stop-opacity: 0;
}

</style>
