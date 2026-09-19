<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEkjNAy)" class="xmzur5cjl"/><path fill="url(#ixt7aDd)" class="xmzur5cjl"/><path fill="url(#iENZaOp)" class="xmzur5cjl"/><path fill="url(#iPkQoHd)" class="lxo_0jbes"/><path fill="url(#iWb6iqb)" class="xmzur5cjl"/><path fill="url(#i4vMrSc)" class="xmzur5cjl"/><path fill="url(#iClHnzc)" class="xmzur5cjl"/><path fill="url(#iaTRiHe)" class="xmzur5cjl"/><path class="q-fdj6b_g"/><path class="nvvlezvyu"/><g filter="url(#ieoGhgd)"><path class="ywdx36wuo"/></g><path stroke="url(#izSTfKc)" class="ia4u16bid"/><path stroke="url(#i2iltLc)" class="ia4u16bid"/><g filter="url(#iiAtQnb)"><path stroke="url(#ijzNHJe)" class="b6sdpb0lm"/></g><path fill="url(#ifS2txe)" class="bhgicjgjg"/><path fill="url(#iLaceJb)" class="bhgicjgjg"/><path fill="url(#iEhxVnb)" class="bhgicjgjg"/><path fill="url(#i9QxuJd)" class="bhgicjgjg"/><path fill="url(#ii69HVd)" class="bhgicjgjg"/><g filter="url(#ipKA4qT)"><path class="lzncrv99g"/></g><path fill="url(#ir83odc)" class="hdenz1kfw"/><path fill="url(#ig8Db6b)" class="hdenz1kfw"/><path fill="url(#izoXQLO)" class="zd5ufn8pt"/><path fill="url(#iMr5Cae)" class="zd5ufn8pt"/><path fill="url(#iFTvUfd)" class="zd5ufn8pt"/><path fill="url(#iG3Nwmc)" class="zd5ufn8pt"/><path fill="url(#iSRYsRd)" class="zd5ufn8pt"/><path fill="url(#iD2LeMm)" class="zd5ufn8pt"/><path fill="url(#i77P0Nd)" class="fdbsosiiv"/><path fill="url(#i1Ec3nb)" class="fdbsosiiv"/><path fill="url(#iBFOUGG)" class="fdbsosiiv"/><path fill="url(#iynm0Sv)" class="fdbsosiiv"/><path fill="url(#iVvOVae)" class="fdbsosiiv"/><path fill="url(#ioX1U8H)" class="fdbsosiiv"/><path class="yifs1iued"/><path fill="url(#iUyVkTc)" class="edjdfk5qi"/><path fill="url(#ibhfO6d)" class="edjdfk5qi"/><path fill="url(#iBRfIsd)" class="edjdfk5qi"/><path fill="url(#iF6IhWd)" class="edjdfk5qi"/><path fill="url(#iOVBBmd)" class="edjdfk5qi"/><path fill="url(#i05TGYd)" class="edjdfk5qi"/><g filter="url(#i0yG2ud)"><path fill="url(#i0CIFwe)" class="bwyjx30ht"/><path fill="url(#iLsnpcb)" class="bwyjx30ht"/><path fill="url(#ipGbI1s)" class="bwyjx30ht"/><path fill="url(#ijUqvRu)" class="bwyjx30ht"/></g><defs><radialGradient id="iEkjNAy" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.359 11.787)scale(31.8522)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ixt7aDd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.298 11.918)scale(33.0797)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iENZaOp" cx="0" cy="0" r="1" gradientTransform="matrix(-2.97263 14.86305 -19.0367 -3.80736 17.977 15.179)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iPkQoHd" cx="0" cy="0" r="1" gradientTransform="rotate(135 6.43 12.301)scale(34.8323)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="iWb6iqb" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.808 20.662)scale(23.9056)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="i4vMrSc" cx="0" cy="0" r="1" gradientTransform="matrix(6.36988 9.34248 -6.7719 4.6172 18.402 18.576)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="iClHnzc" cx="0" cy="0" r="1" gradientTransform="rotate(9.866 -104.093 136.212)scale(9.91374)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="iaTRiHe" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -11.802 32.493)scale(50.1546)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="izSTfKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .67188 -.6058 -.69032 22.491 20.03)" gradientUnits="userSpaceOnUse"><stop class="z0f38dbsk"/><stop offset="1" class="le2kfxnnh"/></radialGradient><radialGradient id="i2iltLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.64063 1.9375 -.67707 .57333 14.538 19.89)" gradientUnits="userSpaceOnUse"><stop class="sy25tfbku"/><stop offset="1" class="cp-75jiuf"/></radialGradient><radialGradient id="iLaceJb" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 -2.6875 2.14102 2.53935 4.611 13.624)" gradientUnits="userSpaceOnUse"><stop class="oaq5bgflq"/><stop offset="1" class="k_nv81btm"/></radialGradient><radialGradient id="iEhxVnb" cx="0" cy="0" r="1" gradientTransform="rotate(130.301 1.968 5.668)scale(6.62467 10.1816)" gradientUnits="userSpaceOnUse"><stop offset=".769" class="mtjixlb5e"/><stop offset="1" class="a9r3-p3pr"/></radialGradient><radialGradient id="i9QxuJd" cx="0" cy="0" r="1" gradientTransform="matrix(3.2508 .70115 -.3739 1.7335 10.028 7.437)" gradientUnits="userSpaceOnUse"><stop class="th1ad00nq"/><stop offset="1" class="irjp2pbpx"/></radialGradient><radialGradient id="ii69HVd" cx="0" cy="0" r="1" gradientTransform="matrix(4.09375 -3.76574 2.15105 2.33842 7.486 12.937)" gradientUnits="userSpaceOnUse"><stop class="z0kt_2b2u"/><stop offset="1" class="nxqoa8b6a"/></radialGradient><radialGradient id="ig8Db6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40624 2.25001 -2.14896 -1.34308 17.299 6.78)" gradientUnits="userSpaceOnUse"><stop class="uu149oiva"/><stop offset="1" class="slk_cbm0c"/></radialGradient><radialGradient id="iMr5Cae" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0625 1.01563 -1.08792 -2.2093 18.658 4.28)" gradientUnits="userSpaceOnUse"><stop class="a4_y8vbcu"/><stop offset="1" class="b6_yygb4d"/></radialGradient><radialGradient id="iG3Nwmc" cx="0" cy="0" r="1" gradientTransform="matrix(3.00402 -3.3837 4.37322 3.88252 13.76 8.65)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="lnaxvrb4o"/><stop offset="1" class="ostg23lzo"/></radialGradient><radialGradient id="iD2LeMm" cx="0" cy="0" r="1" gradientTransform="matrix(-4.85935 2.76566 -1.4409 -2.53172 17.877 5.312)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="zf424w2lq"/><stop offset=".922" class="th1ad00nq"/></radialGradient><radialGradient id="i1Ec3nb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90626 1.06249 -1.16524 -2.0906 18.018 2.718)" gradientUnits="userSpaceOnUse"><stop class="a4_y8vbcu"/><stop offset="1" class="b6_yygb4d"/></radialGradient><radialGradient id="iynm0Sv" cx="0" cy="0" r="1" gradientTransform="rotate(-49.636 14.827 -10.248)scale(4.51151 5.7955)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="lnaxvrb4o"/><stop offset="1" class="ostg23lzo"/></radialGradient><radialGradient id="ioX1U8H" cx="0" cy="0" r="1" gradientTransform="matrix(-5.28123 3.28127 -1.97232 -3.17447 17.033 3.812)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="zf424w2lq"/><stop offset=".922" class="th1ad00nq"/></radialGradient><radialGradient id="iUyVkTc" cx="0" cy="0" r="1" gradientTransform="matrix(4.45392 -.89237 .8955 4.46951 10.889 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="njg5t5byh"/><stop offset="1" class="wggpc8ivz"/></radialGradient><radialGradient id="iBRfIsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3704 3.66512 -5.32541 -1.9912 12.243 4.139)" gradientUnits="userSpaceOnUse"><stop offset=".842" class="irjp2pbpx"/><stop offset="1" class="th1ad00nq"/></radialGradient><radialGradient id="iF6IhWd" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.20704 .28715 1.1702 11.707 5.27)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="w24jbob3f"/><stop offset="1" class="cov7hmbxs"/></radialGradient><radialGradient id="i05TGYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82812 1.01564 -1.222 -2.19958 14.846 3.546)" gradientUnits="userSpaceOnUse"><stop class="ihd390cfw"/><stop offset="1" class="t9zkmquqg"/></radialGradient><radialGradient id="iLsnpcb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43751 1.37498 -1.39761 -2.47763 11.799 4.561)" gradientUnits="userSpaceOnUse"><stop class="h6a-ozyxn"/><stop offset="1" class="k7_83qzqr"/></radialGradient><radialGradient id="ipGbI1s" cx="0" cy="0" r="1" gradientTransform="matrix(-.625 -1.125 4.5106 -2.50593 9.08 8.061)" gradientUnits="userSpaceOnUse"><stop class="a-45wkben"/><stop offset="1" class="cx2fhfbqo"/></radialGradient><radialGradient id="ijUqvRu" cx="0" cy="0" r="1" gradientTransform="matrix(-.24218 -.40625 2.97413 -1.77301 10.197 7.522)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="hy-3a5b0d"/><stop offset="1" class="t2806yvzw"/></radialGradient><linearGradient id="ijzNHJe" x1="15.116" x2="18.163" y1="20.686" y2="22.171" gradientUnits="userSpaceOnUse"><stop class="c6-94vbwc"/><stop offset="1" class="k3vhuof5y"/></linearGradient><linearGradient id="ifS2txe" x1="8.781" x2="4.049" y1="8.905" y2="11.593" gradientUnits="userSpaceOnUse"><stop class="l_ujgfbqv"/><stop offset="1" class="jeqf4qb-v"/></linearGradient><linearGradient id="ir83odc" x1="12.267" x2="14.267" y1="9.906" y2="10.406" gradientUnits="userSpaceOnUse"><stop offset=".316" class="f71zwr8du"/><stop offset="1" class="hf_7yabmx"/></linearGradient><linearGradient id="izoXQLO" x1="18.378" x2="11.936" y1="3.855" y2="8.217" gradientUnits="userSpaceOnUse"><stop class="pa16thbqb"/><stop offset="1" class="jwj1owbyh"/></linearGradient><linearGradient id="iFTvUfd" x1="15.848" x2="17.159" y1="3.514" y2="4.77" gradientUnits="userSpaceOnUse"><stop class="u4a3qgo2u"/><stop offset=".851" class="wtvs4fopy"/></linearGradient><linearGradient id="iSRYsRd" x1="16.812" x2="16.466" y1="7.143" y2="6.546" gradientUnits="userSpaceOnUse"><stop class="oiszdccap"/><stop offset="1" class="f3ica6bvv"/></linearGradient><linearGradient id="i77P0Nd" x1="17.525" x2="11.091" y1="2.814" y2="6.986" gradientUnits="userSpaceOnUse"><stop class="pa16thbqb"/><stop offset="1" class="jwj1owbyh"/></linearGradient><linearGradient id="iBFOUGG" x1="15.065" x2="16.393" y1="2.468" y2="3.687" gradientUnits="userSpaceOnUse"><stop class="u4a3qgo2u"/><stop offset=".851" class="wtvs4fopy"/></linearGradient><linearGradient id="iVvOVae" x1="16.002" x2="15.643" y1="6.155" y2="5.562" gradientUnits="userSpaceOnUse"><stop class="oiszdccap"/><stop offset="1" class="f3ica6bvv"/></linearGradient><linearGradient id="ibhfO6d" x1="12.471" x2="12.143" y1="7.046" y2="6.499" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bfff1cceu"/><stop offset="1" class="nb6_09bfk"/></linearGradient><linearGradient id="iOVBBmd" x1="11.361" x2="12.377" y1="3.53" y2="4.624" gradientUnits="userSpaceOnUse"><stop offset=".048" class="f_0an1zxx"/><stop offset="1" class="wtzd4lbuc"/></linearGradient><linearGradient id="i0CIFwe" x1="11.299" x2="2.134" y1="4.811" y2="10.749" gradientUnits="userSpaceOnUse"><stop class="pa16thbqb"/><stop offset="1" class="jwj1owbyh"/></linearGradient><filter id="ieoGhgd" width="9.819" height="3.981" x="13.192" y="19.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.203922 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_14396_1026"/></filter><filter id="iiAtQnb" width="9.469" height="3.281" x="13.242" y="19.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_14396_1026" stdDeviation=".25"/></filter><filter id="ipKA4qT" width="6.439" height="5.409" x="11.259" y="5.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.635294 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_14396_1026"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.541176 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_14396_1026" result="effect2_innerShadow_14396_1026"/></filter><filter id="i0yG2ud" width="10.41" height="8.555" x="2.134" y="3.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.654902 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_14396_1026"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:saluting-face" /></template>
<style>
.a-45wkben {
  stop-color: var(--svg-color--fea24f, #FEA24F);
}

.a4_y8vbcu {
  stop-color: var(--svg-color--fff064, #FFF064);
}

.a9r3-p3pr {
  stop-color: var(--svg-color--d1a64e, #D1A64E);
}

.b6_yygb4d {
  stop-color: var(--svg-color--feba32, #FEBA32);
  stop-opacity: 0;
}

.b6sdpb0lm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M13.992 20.39c.459.593 1.887 1.78 3.932 1.78s3.543-1.187 4.037-1.78");
}

.bfff1cceu {
  stop-color: var(--svg-color--f09a35, #F09A35);
}

.bhgicjgjg {
  d: path("M4.127 13.108c-.963-.325-1.453-.93-1.613-1.242l5.02-5.383l6.687-1.39l.828 2.922l-3.578 2.984c-1 .425-3.604 1.458-4.782 1.922c-.453.198-1.6.512-2.562.187");
}

.bwyjx30ht {
  d: path("M11.065 6.905C8.939 8.195 4.614 10.74 2.588 12c-.453-.594-.763-1.915.055-3.125c1.367-2.024 3.015-2.72 3.984-3.157a80 80 0 0 0 3-1.813c.926-.59 1.91-.277 2.371.399c.441.646.574 1.78-.933 2.601");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.c6-94vbwc {
  stop-color: var(--svg-color--56404e, #56404E);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cov7hmbxs {
  stop-color: var(--svg-color--ffa80f, #FFA80F);
  stop-opacity: 0;
}

.cp-75jiuf {
  stop-color: var(--svg-color--57434c, #57434C);
  stop-opacity: 0;
}

.cx2fhfbqo {
  stop-color: var(--svg-color--fea24f, #FEA24F);
  stop-opacity: 0;
}

.edjdfk5qi {
  d: path("M9.984 7.195a.99.99 0 0 0 1.359.327c1.01-.615 2.225-1.37 2.776-1.704c1.485-.842 1.375-1.955.934-2.601c-.461-.676-1.445-.989-2.371-.399c-.729.465-3.196 1.947-3.938 2.376z");
}

.f_0an1zxx {
  stop-color: var(--svg-color--c6a253, #C6A253);
}

.f3ica6bvv {
  stop-color: var(--svg-color--f19b3a, #F19B3A);
  stop-opacity: 0;
}

.f71zwr8du {
  stop-color: var(--svg-color--ffb032, #FFB032);
}

.fdbsosiiv {
  d: path("M12.846 7.858c1.05-.625 3.437-2.15 4.156-2.587c1.484-.842 1.375-1.955.934-2.601c-.461-.676-1.446-.988-2.371-.399c-.73.465-3.735 2.322-4.477 2.751z");
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

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h6a-ozyxn {
  stop-color: var(--svg-color--fff166, #FFF166);
}

.hdenz1kfw {
  d: path("M11.26 11.054c1.351-.406 3.164-1.086 4.71-1.719c1.61-.567 1.7-1.751 1.38-2.465c-.334-.747-1.276-1.18-2.291-.762c-.8.328-1.112 1.11-1.042 2.063z");
}

.hf_7yabmx {
  stop-color: var(--svg-color--ffc946, #FFC946);
  stop-opacity: 0;
}

.hy-3a5b0d {
  stop-color: var(--svg-color--f19b3d, #F19B3D);
}

.ia4u16bid {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-6px, 1.6px);
  d: path("M13.992 20.53c.459.594 1.887 1.781 3.932 1.781s3.543-1.187 4.037-1.78");
}

.ihd390cfw {
  stop-color: var(--svg-color--fff266, #FFF266);
}

.irjp2pbpx {
  stop-color: var(--svg-color--ffb639, #FFB639);
  stop-opacity: 0;
}

.jeqf4qb-v {
  stop-color: var(--svg-color--f1a530, #F1A530);
}

.jwj1owbyh {
  stop-color: var(--svg-color--f0a42f, #F0A42F);
}

.k_nv81btm {
  stop-color: var(--svg-color--ee9654, #EE9654);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k3vhuof5y {
  stop-color: var(--svg-color--56404e, #56404E);
  stop-opacity: 0;
}

.k7_83qzqr {
  stop-color: var(--svg-color--ffbb32, #FFBB32);
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.l_ujgfbqv {
  stop-color: var(--svg-color--ffb438, #FFB438);
}

.le2kfxnnh {
  stop-color: var(--svg-color--5f4e50, #5F4E50);
  stop-opacity: 0;
}

.lnaxvrb4o {
  stop-color: var(--svg-color--fda04c, #FDA04C);
}

.lxo_0jbes {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M17.976 30.04c7.928 0 11.89-5.323 11.89-11.89c0-6.566-3.962-11.89-11.89-11.89c-7.927 0-11.89 5.324-11.89 11.89s3.963 11.89 11.89 11.89");
}

.lzncrv99g {
  fill: var(--svg-color--ffc744, #FFC744);
  d: path("M11.26 11.054c1.351-.406 3.164-1.086 4.71-1.719c1.61-.567 1.7-1.751 1.38-2.465c-.334-.747-1.276-1.18-2.291-.762c-.8.328-1.112 1.11-1.042 2.063z");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mtjixlb5e {
  stop-color: var(--svg-color--f3a731, #F3A731);
  stop-opacity: 0;
}

.nb6_09bfk {
  stop-color: var(--svg-color--f09a35, #F09A35);
  stop-opacity: 0;
}

.njg5t5byh {
  stop-color: var(--svg-color--fc9f4d, #FC9F4D);
}

.nvvlezvyu {
  fill: var(--svg-color--402931, #402931);
  d: path("M19.638 14.673a2.534 2.534 0 1 0 5.068 0a2.534 2.534 0 0 0-5.068 0m-3.323 0a2.534 2.534 0 1 1-5.068 0a2.534 2.534 0 0 1 5.068 0");
}

.nxqoa8b6a {
  stop-color: var(--svg-color--f7a23e, #F7A23E);
  stop-opacity: 0;
}

.oaq5bgflq {
  stop-color: var(--svg-color--ee9654, #EE9654);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.oiszdccap {
  stop-color: var(--svg-color--f19b3a, #F19B3A);
}

.ostg23lzo {
  stop-color: var(--svg-color--fda04c, #FDA04C);
  stop-opacity: 0;
}

.pa16thbqb {
  stop-color: var(--svg-color--ffbc32, #FFBC32);
}

.q-fdj6b_g {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.098 14.673a3.59 3.59 0 1 0 7.179 0a3.59 3.59 0 0 0-7.179 0m-2.243 0a3.59 3.59 0 1 1-7.179 0a3.59 3.59 0 0 1 7.179 0");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.slk_cbm0c {
  stop-color: var(--svg-color--ffc744, #FFC744);
  stop-opacity: 0;
}

.sy25tfbku {
  stop-color: var(--svg-color--57434c, #57434C);
}

.t2806yvzw {
  stop-color: var(--svg-color--f19b3d, #F19B3D);
  stop-opacity: 0;
}

.t9zkmquqg {
  stop-color: var(--svg-color--ffc033, #FFC033);
  stop-opacity: 0;
}

.th1ad00nq {
  stop-color: var(--svg-color--ffb639, #FFB639);
}

.u4a3qgo2u {
  stop-color: var(--svg-color--c7a357, #C7A357);
}

.uu149oiva {
  stop-color: var(--svg-color--ffe667, #FFE667);
}

.w24jbob3f {
  stop-color: var(--svg-color--ffa80f, #FFA80F);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wggpc8ivz {
  stop-color: var(--svg-color--fc9f4d, #FC9F4D);
  stop-opacity: 0;
}

.wtvs4fopy {
  stop-color: var(--svg-color--ffc42d, #FFC42D);
  stop-opacity: 0;
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.xmzur5cjl {
  d: path("M17.976 30.04c7.928 0 11.89-5.323 11.89-11.89c0-6.566-3.962-11.89-11.89-11.89c-7.927 0-11.89 5.324-11.89 11.89s3.963 11.89 11.89 11.89");
}

.yifs1iued {
  fill: var(--svg-color--ffc52f, #FFC52F);
  d: path("M9.984 7.195a.99.99 0 0 0 1.359.327c1.01-.615 2.225-1.37 2.776-1.704c1.485-.842 1.375-1.955.934-2.601c-.461-.676-1.445-.989-2.371-.399c-.729.465-3.196 1.947-3.938 2.376z");
}

.ywdx36wuo {
  stroke: var(--svg-color--4d264e, #4D264E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-6px, 1.6px);
  d: path("M13.992 20.53c.459.594 1.887 1.781 3.932 1.781s3.543-1.187 4.037-1.78");
}

.z0f38dbsk {
  stop-color: var(--svg-color--5f4e50, #5F4E50);
}

.z0kt_2b2u {
  stop-color: var(--svg-color--f7a23e, #F7A23E);
}

.zd5ufn8pt {
  d: path("M13.44 8.82c1.049-.626 3.484-2.078 4.468-2.563c1.484-.842 1.324-1.923.883-2.57c-.46-.676-1.465-.935-2.39-.345c-.73.465-3.9 2.338-4.641 2.767z");
}

.zf424w2lq {
  stop-color: var(--svg-color--ffa24e, #FFA24E);
  stop-opacity: 0;
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
