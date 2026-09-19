<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#iUQOPic)" class="wbzw-bbbe"/><path fill="url(#iGCY4Xv)" class="u85nt16hr"/><path fill="url(#iT7i4Cp)" class="tbabrkbve"/><path fill="url(#iQSnvqd)" class="ol64iabsv"/><path fill="url(#iBDJqtC)" class="g67eryn7z"/><path fill="url(#iaLCR9c)" class="o_-7anb_h"/><ellipse fill="url(#imJoBKe)" transform="rotate(-45 9.432 9.31)" class="jzxtktztw"/><ellipse fill="url(#ibekJzd)" transform="rotate(-12.966 20.92 9.198)" class="jwzxvqb8m"/><circle fill="url(#iJt98qp)" transform="rotate(45 13.078 7.624)" class="o-vx12drz"/><ellipse fill="url(#i6vmdZc)" transform="rotate(45 24.371 8.624)" class="q9a-rxbsr"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iUQOPic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11 22 0 16 27)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="iT7i4Cp" cx="0" cy="0" r="1" gradientTransform="matrix(-11.99998 -5.5001 2.2862 -4.98797 14 14)" gradientUnits="userSpaceOnUse"><stop class="z3kb90exn"/><stop offset="1" class="ozk-jcbqz"/></radialGradient><radialGradient id="iQSnvqd" cx="0" cy="0" r="1" gradientTransform="rotate(122.005 6.952 11.043)scale(4.71699)" gradientUnits="userSpaceOnUse"><stop class="xjyer8b8q"/><stop offset="1" class="lxsk2wb0p"/></radialGradient><radialGradient id="imJoBKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.10148 -1.5764 0 9.432 9.31)" gradientUnits="userSpaceOnUse"><stop class="qucx3pbkh"/><stop offset="1" class="j9q68nyuf"/></radialGradient><radialGradient id="ibekJzd" cx="0" cy="0" r="1" gradientTransform="matrix(.41355 2.66063 -1.8031 .28026 21.043 9.024)" gradientUnits="userSpaceOnUse"><stop class="qucx3pbkh"/><stop offset=".26" class="qucx3pbkh"/><stop offset="1" class="j9q68nyuf"/></radialGradient><radialGradient id="iJt98qp" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.727 10.351)scale(1.5)" gradientUnits="userSpaceOnUse"><stop class="qucx3pbkh"/><stop offset="1" class="j9q68nyuf"/></radialGradient><radialGradient id="i6vmdZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -1 0 24.371 8.624)" gradientUnits="userSpaceOnUse"><stop class="qucx3pbkh"/><stop offset="1" class="j9q68nyuf"/></radialGradient><linearGradient id="iGCY4Xv" x1="16" x2="16" y1="16" y2="17.5" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="iBDJqtC" x1="12.986" x2="9.986" y1="7" y2="14" gradientUnits="userSpaceOnUse"><stop class="u1fm6pgvn"/><stop offset="1" class="h13dd1l8r"/></linearGradient><linearGradient id="iaLCR9c" x1="24" x2="19" y1="7" y2="15" gradientUnits="userSpaceOnUse"><stop class="u1fm6pgvn"/><stop offset="1" class="h13dd1l8r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:smiling-face-with-heart-eyes" /></template>
<style>
.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.g67eryn7z {
  d: path("M10.593 14.27c-1.046-.33-2.808-1.078-4.157-2.636c-2.09-2.412-.139-5.867 3.55-4.134c1.577-2.572 5.49-1.62 4.97 1.5c-.349 2.09-1.895 3.937-2.802 4.866a1.53 1.53 0 0 1-1.561.404");
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.j9q68nyuf {
  stop-color: var(--svg-color--ec6686, #EC6686);
  stop-opacity: 0;
}

.jwzxvqb8m {
  cx: 20.919px;
  cy: 9.198px;
  rx: 2px;
  ry: 3px;
}

.jzxtktztw {
  cx: 9.432px;
  cy: 9.311px;
  rx: 1.5px;
  ry: 3px;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.lxsk2wb0p {
  stop-color: var(--svg-color--fba84c, #FBA84C);
  stop-opacity: 0;
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.o_-7anb_h {
  d: path("M21.41 14.27c1.046-.33 2.808-1.078 4.157-2.636c2.09-2.412.14-5.867-3.55-4.134c-1.577-2.572-5.49-1.62-4.97 1.5c.349 2.09 1.895 3.937 2.802 4.866c.41.419 1.003.58 1.561.404");
}

.o-vx12drz {
  cx: 13.078px;
  cy: 7.624px;
  r: 1.5px;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ol64iabsv {
  d: path("M19.517 15.5s3-.5 5.05-2.866c2.09-2.412.14-5.867-3.55-4.134c-1.577-2.572-5.49-1.62-4.97 1.5c.5 3 3.47 5.5 3.47 5.5");
}

.ozk-jcbqz {
  stop-color: var(--svg-color--e6872b, #E6872B);
  stop-opacity: 0;
}

.q9a-rxbsr {
  cx: 24.371px;
  cy: 8.624px;
  rx: 1px;
  ry: 2px;
}

.qucx3pbkh {
  stop-color: var(--svg-color--ec6686, #EC6686);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.tbabrkbve {
  d: path("M10.5 15.5s-3-.5-5.05-2.866C3.36 10.222 5.311 6.767 9 8.5c1.577-2.572 5.49-1.62 4.97 1.5c-.5 3-3.47 5.5-3.47 5.5");
}

.u1fm6pgvn {
  stop-color: var(--svg-color--ca0b4a, #CA0B4A);
}

.u85nt16hr {
  d: path("M8 16.5V16h16v.5a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wbzw-bbbe {
  d: path("M16 25c-9 0-9-9-9-9h18s0 9-9 9");
}

.xjyer8b8q {
  stop-color: var(--svg-color--ec812a, #EC812A);
}

.z3kb90exn {
  stop-color: var(--svg-color--cc7521, #CC7521);
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
