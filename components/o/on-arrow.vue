<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="v49rijbhc"/><path class="fghs7py2v"/><path fill="url(#i0w0Wce)" class="hpbl5mn4f"/><path fill="url(#imV14RU)" class="hpbl5mn4f"/><path class="f02ndvb_r"/><path fill="url(#ijhy7cb)" class="nmps2kbpv"/><path fill="url(#iH7xxzc)" class="nmps2kbpv"/><path fill="url(#ipo10sd)" class="nmps2kbpv"/><path fill="url(#inShYhe)" class="nmps2kbpv"/><path fill="url(#i95qavb)" class="nmps2kbpv"/><path fill="url(#iNhOnkd)" class="nmps2kbpv"/><path fill="url(#igGxW4c)" class="nmps2kbpv"/><path fill="url(#ivazAve)" class="nmps2kbpv"/><path fill="url(#i3Eb9Rd)" class="nmps2kbpv"/><path fill="url(#ic5NCbe)" class="nmps2kbpv"/><path class="lzfks5b3v"/><path fill="url(#iVFrKMd)" class="a_zprnrwk"/><path fill="url(#ipv600d)" class="a_zprnrwk"/><path fill="url(#iueVwhc)" class="a_zprnrwk"/><path fill="url(#i5wQGcn)" class="a_zprnrwk"/><path fill="url(#iMbS5HU)" class="a_zprnrwk"/><path fill="url(#iBxUq6P)" class="a_zprnrwk"/><path fill="url(#i1FBLDc)" class="a_zprnrwk"/><path fill="url(#iavfFgb)" class="a_zprnrwk"/><defs><radialGradient id="imV14RU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53125 30.3188 0 16.335 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="s1u8bgjjw"/><stop offset=".633" class="wojg51b7g"/><stop offset="1" class="w95b-ztnx"/></radialGradient><radialGradient id="ijhy7cb" cx="0" cy="0" r="1" gradientTransform="rotate(130.601 -.764 7.259)scale(2.01678 18.4341)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="oir76sqmm"/><stop offset=".528" class="x7eikgb-u"/><stop offset="1" class="ap-i9rbmn"/></radialGradient><radialGradient id="iH7xxzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21875 4.0625 -2.0599 -.11092 11.219 3.688)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="f6i2duyld"/><stop offset="1" class="s3sd9uv-y"/></radialGradient><radialGradient id="ipo10sd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 1.46875 -12.02523 10.4901 3.938 6.344)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="ad3ffbcvf"/><stop offset="1" class="yhyazbcky"/></radialGradient><radialGradient id="inShYhe" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 4.6875 -.995 -.00663 11 3.281)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="qlxnqpy4v"/><stop offset="1" class="hv7k72bel"/></radialGradient><radialGradient id="i95qavb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45313 .6875 -.28223 -.18602 10.061 2.765)" gradientUnits="userSpaceOnUse"><stop class="goz-mx0tw"/><stop offset="1" class="zf_jv2vmi"/></radialGradient><radialGradient id="iNhOnkd" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.75 -1.18286 .69704 11.023 6.18)" gradientUnits="userSpaceOnUse"><stop class="qvuc3k65w"/><stop offset="1" class="d_3okdntd"/></radialGradient><radialGradient id="igGxW4c" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 1.875 -1.2366 .52556 11.438 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="diba8iggl"/><stop offset="1" class="bw6zsabyg"/></radialGradient><radialGradient id="ivazAve" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.34375 -1.97452 -.1053 11.5 12.906)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="m0mjg3bfp"/><stop offset=".567" class="wojg51b7g"/><stop offset=".825" class="grm0g-4db"/></radialGradient><radialGradient id="i3Eb9Rd" cx="0" cy="0" r="1" gradientTransform="matrix(.18752 4.28125 -1.38662 .06074 10.907 14.969)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="fnknxorxz"/><stop offset="1" class="jg9jk97fk"/></radialGradient><radialGradient id="ic5NCbe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.511 9.636 5.018)scale(.95159 .4562)" gradientUnits="userSpaceOnUse"><stop class="z349tsbtk"/><stop offset="1" class="om0q0xbfn"/></radialGradient><radialGradient id="iVFrKMd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 1.15624 -13.99713 -13.24059 25.593 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="ycoup5wdj"/><stop offset=".453" class="tpnkh7byy"/><stop offset="1" class="vlztjhb3c"/></radialGradient><radialGradient id="ipv600d" cx="0" cy="0" r="1" gradientTransform="rotate(133.781 12.053 7.896)scale(1.2985 20.7628)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="wz9b_e0-w"/><stop offset="1" class="vlztjhb3c"/><stop offset="1" class="jedx2ccyq"/></radialGradient><radialGradient id="iueVwhc" cx="0" cy="0" r="1" gradientTransform="rotate(47.643 -2.588 36.284)scale(1.43784 24.393)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="oir76sqmm"/><stop offset=".528" class="x7eikgb-u"/><stop offset="1" class="ap-i9rbmn"/></radialGradient><radialGradient id="i5wQGcn" cx="0" cy="0" r="1" gradientTransform="matrix(.57031 4.1875 -2.26615 .30864 20.39 3.625)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="nfg576bur"/><stop offset=".931" class="fh3236buo"/></radialGradient><radialGradient id="iMbS5HU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10937 0 0 -.53737 20.39 7.469)" gradientUnits="userSpaceOnUse"><stop class="bpg2ifbok"/><stop offset="1" class="nmnhuhcpf"/></radialGradient><radialGradient id="iBxUq6P" cx="0" cy="0" r="1" gradientTransform="rotate(103.917 5.327 14.295)scale(1.81902 1.60757)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="m0mjg3bfp"/><stop offset=".567" class="wojg51b7g"/><stop offset=".825" class="grm0g-4db"/></radialGradient><radialGradient id="i1FBLDc" cx="0" cy="0" r="1" gradientTransform="matrix(.0313 4.85937 -1.57494 .01014 21.235 14.906)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="h6i26wb8o"/><stop offset="1" class="jg9jk97fk"/></radialGradient><radialGradient id="iavfFgb" cx="0" cy="0" r="1" gradientTransform="matrix(.29687 -.65625 .44409 .2009 21.984 15.875)" gradientUnits="userSpaceOnUse"><stop class="z349tsbtk"/><stop offset="1" class="om0q0xbfn"/></radialGradient><linearGradient id="i0w0Wce" x1="16.36" x2="16.36" y1="6.391" y2="8.188" gradientUnits="userSpaceOnUse"><stop offset=".116" class="t0-y0kktv"/><stop offset=".513" class="h7bpaob4x"/><stop offset=".652" class="h7bpaob4x"/><stop offset="1" class="eyv78ib6z"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:on-arrow" /></template>
<style>
.a_zprnrwk {
  d: path("m22.59 2.224l7.14 6.5c.36.32.36.89 0 1.21l-7.14 6.5c-.53.48-1.38.1-1.38-.61v-2.85c0-.45-.37-.82-.82-.82v-5.65c.45 0 .82-.37.82-.82v-2.85c0-.72.85-1.09 1.38-.61");
}

.ad3ffbcvf {
  stop-color: var(--svg-color--483f6e, #483F6E);
}

.ap-i9rbmn {
  stop-color: var(--svg-color--7647cd, #7647CD);
  stop-opacity: 0;
}

.bpg2ifbok {
  stop-color: var(--svg-color--8a7ec6, #8A7EC6);
}

.bw6zsabyg {
  stop-color: var(--svg-color--6454a2, #6454A2);
  stop-opacity: 0;
}

.d_3okdntd {
  stop-color: var(--svg-color--a297d5, #A297D5);
  stop-opacity: 0;
}

.diba8iggl {
  stop-color: var(--svg-color--6454a2, #6454A2);
}

.eyv78ib6z {
  stop-color: var(--svg-color--7e6bc5, #7E6BC5);
  stop-opacity: 0;
}

.f02ndvb_r {
  fill: var(--svg-color--7e6cc2, #7E6CC2);
  d: path("M11.61 12.154c-.45 0-.82.37-.82.82v2.85c0 .72-.85 1.09-1.38.61l-7.14-6.5a.824.824 0 0 1 0-1.22l7.14-6.5c.53-.48 1.38-.1 1.38.61v2.86c0 .45.37.82.82.82z");
}

.f6i2duyld {
  stop-color: var(--svg-color--968acd, #968ACD);
}

.fghs7py2v {
  fill: var(--svg-color--7e6bc5, #7E6BC5);
  d: path("M21.21 12.974c0-.45-.37-.82-.82-.82h-8.78c-.45 0-.82.37-.82.82v-7.29c0 .45.37.82.82.82h8.78c.45 0 .82-.37.82-.82z");
}

.fh3236buo {
  stop-color: var(--svg-color--6d5dad, #6D5DAD);
  stop-opacity: 0;
}

.fnknxorxz {
  stop-color: var(--svg-color--5e4ba1, #5E4BA1);
}

.ft5dv1b6b {
  fill: none;
}

.goz-mx0tw {
  stop-color: var(--svg-color--a096d0, #A096D0);
}

.grm0g-4db {
  stop-color: var(--svg-color--8155d1, #8155D1);
  stop-opacity: 0;
}

.h6i26wb8o {
  stop-color: var(--svg-color--4f3c90, #4F3C90);
}

.h7bpaob4x {
  stop-color: var(--svg-color--8a7ec5, #8A7EC5);
}

.hpbl5mn4f {
  d: path("M21.21 12.974c0-.45-.37-.82-.82-.82h-8.78c-.45 0-.82.37-.82.82v-7.29c0 .45.37.82.82.82h8.78c.45 0 .82-.37.82-.82z");
}

.hv7k72bel {
  stop-color: var(--svg-color--6e5daf, #6E5DAF);
  stop-opacity: 0;
}

.jedx2ccyq {
  stop-color: var(--svg-color--7062a8, #7062A8);
  stop-opacity: 0;
}

.jg9jk97fk {
  stop-color: var(--svg-color--7e6cc3, #7E6CC3);
  stop-opacity: 0;
}

.lzfks5b3v {
  fill: var(--svg-color--7e6bc5, #7E6BC5);
  d: path("m22.59 2.224l7.14 6.5c.36.32.36.89 0 1.21l-7.14 6.5c-.53.48-1.38.1-1.38-.61v-2.85c0-.45-.37-.82-.82-.82v-5.65c.45 0 .82-.37.82-.82v-2.85c0-.72.85-1.09 1.38-.61");
}

.m0mjg3bfp {
  stop-color: var(--svg-color--5f36ba, #5F36BA);
}

.nfg576bur {
  stop-color: var(--svg-color--4f3f88, #4F3F88);
}

.nmnhuhcpf {
  stop-color: var(--svg-color--8a7ec6, #8A7EC6);
  stop-opacity: 0;
}

.nmps2kbpv {
  d: path("M11.61 12.154c-.45 0-.82.37-.82.82v2.85c0 .72-.85 1.09-1.38.61l-7.14-6.5a.824.824 0 0 1 0-1.22l7.14-6.5c.53-.48 1.38-.1 1.38.61v2.86c0 .45.37.82.82.82z");
}

.oir76sqmm {
  stop-color: var(--svg-color--5836ab, #5836AB);
}

.om0q0xbfn {
  stop-color: var(--svg-color--8e4fec, #8E4FEC);
  stop-opacity: 0;
}

.qlxnqpy4v {
  stop-color: var(--svg-color--62529f, #62529F);
}

.qvuc3k65w {
  stop-color: var(--svg-color--a297d5, #A297D5);
}

.s1u8bgjjw {
  stop-color: var(--svg-color--5e36b9, #5E36B9);
}

.s3sd9uv-y {
  stop-color: var(--svg-color--897dc2, #897DC2);
  stop-opacity: 0;
}

.t0-y0kktv {
  stop-color: var(--svg-color--6454a3, #6454A3);
}

.tpnkh7byy {
  stop-color: var(--svg-color--998ed2, #998ED2);
}

.v49rijbhc {
  fill: var(--svg-color--7763bb, #7763BB);
  d: path("M22.59 26.514c0 .55.45 1 1 1c.56 0 1-.44 1-1v-4.81c0-.55-.45-1-1-1s-1 .45-1 1zm-2.12 3.49c-.33 0-.65-.16-.84-.45l-2.95-4.49v3.94c0 .55-.45 1-1 1s-1-.45-1-1v-7.29c0-.44.29-.83.71-.96s.88.04 1.12.41l2.95 4.49v-3.94c0-.55.45-1 1-1s1 .45 1 1v7.29c0 .44-.29.83-.71.96c-.09.03-.18.04-.28.04m-9.88 0c-1.75 0-3.18-1.43-3.18-3.18v-2.93c0-1.75 1.43-3.18 3.18-3.18s3.18 1.43 3.18 3.18v2.93c0 1.75-1.43 3.18-3.18 3.18m0-7.29c-.65 0-1.18.53-1.18 1.18v2.93c0 .65.53 1.18 1.18 1.18s1.18-.53 1.18-1.18v-2.93c0-.65-.53-1.18-1.18-1.18m13 7.29a.91.91 0 1 0 0-1.82a.91.91 0 0 0 0 1.82");
}

.vlztjhb3c {
  stop-color: var(--svg-color--8677c6, #8677C6);
  stop-opacity: 0;
}

.w95b-ztnx {
  stop-color: var(--svg-color--8d50ed, #8D50ED);
  stop-opacity: 0;
}

.wojg51b7g {
  stop-color: var(--svg-color--8d50ed, #8D50ED);
}

.wz9b_e0-w {
  stop-color: var(--svg-color--7062a8, #7062A8);
}

.x7eikgb-u {
  stop-color: var(--svg-color--7647cd, #7647CD);
}

.ycoup5wdj {
  stop-color: var(--svg-color--9d92d4, #9D92D4);
}

.yhyazbcky {
  stop-color: var(--svg-color--5f5395, #5F5395);
  stop-opacity: 0;
}

.z349tsbtk {
  stop-color: var(--svg-color--8e4fec, #8E4FEC);
}

.zf_jv2vmi {
  stop-color: var(--svg-color--a096d0, #A096D0);
  stop-opacity: 0;
}

</style>
