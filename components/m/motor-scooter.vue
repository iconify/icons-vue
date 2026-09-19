<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAnIaPb)" class="yscgurb3c"/><path fill="url(#iSniYJd)" class="yscgurb3c"/><path fill="url(#ioFkUxe)" class="yscgurb3c"/><path fill="url(#iCFWRMe)" class="yscgurb3c"/><g clip-rule="evenodd" filter="url(#ilezOub)" class="d2kvgvbvc"><path fill="url(#iex1pmc)" class="xl9f4fbyk"/><path fill="url(#ite120c)" class="xl9f4fbyk"/><path fill="url(#iW54lkb)" class="xl9f4fbyk"/></g><path fill="url(#ixqqWNF)" class="nncn12fxv"/><circle fill="url(#inxfYAe)" class="k2aeny25u"/><g filter="url(#iySr6Oe)"><circle stroke="url(#iSjZ2wR)" class="d_h9nrb1p"/></g><circle fill="url(#ixcdyed)" class="eefp3crkp"/><circle class="nmmi8v6ew"/><g filter="url(#iIGIlNQ)"><circle fill="url(#iVEx6eU)" class="plm1ecbru"/></g><g filter="url(#ibl58Fc)"><circle stroke="url(#i5bwPXj)" class="guza7pc9a"/></g><rect fill="url(#iwUbZue)" class="rf43v0b_j"/><rect fill="url(#ikAfObe)" class="rf43v0b_j"/><g filter="url(#iFFur5c)"><path fill="url(#iufOelb)" class="fhn790bpu"/><path fill="url(#iCxNa0c)" class="fhn790bpu"/></g><g filter="url(#ik8NsTc)"><path fill="url(#inuC9mc)" class="xtvruf4xi"/></g><defs><radialGradient id="iSniYJd" cx="0" cy="0" r="1" gradientTransform="matrix(2.17696 -1.21722 .99003 1.77063 14.804 16.114)" gradientUnits="userSpaceOnUse"><stop class="l2198zboi"/><stop offset="1" class="qp_naeopl"/></radialGradient><radialGradient id="ioFkUxe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13015 -.98314 .2946 -.6383 23.22 15.997)" gradientUnits="userSpaceOnUse"><stop class="m674nab1b"/><stop offset="1" class="fh6o-nbvu"/></radialGradient><radialGradient id="iex1pmc" cx="0" cy="0" r="1" gradientTransform="matrix(9.5 -10.0625 13.7443 12.97599 12.857 26.042)" gradientUnits="userSpaceOnUse"><stop class="l0kfffz0u"/><stop offset="1" class="r_5ts0szz"/></radialGradient><radialGradient id="ite120c" cx="0" cy="0" r="1" gradientTransform="rotate(120.651 1.65 8.16)scale(2.50663 2.58171)" gradientUnits="userSpaceOnUse"><stop class="m2fhst2tl"/><stop offset="1" class="eqcd70b8h"/></radialGradient><radialGradient id="iW54lkb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55804 0 0 -4.44755 19.45 24.705)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="m-je2jb8l"/><stop offset="1" class="m0qscobul"/></radialGradient><radialGradient id="iVEx6eU" cx="0" cy="0" r="1" gradientTransform="rotate(-90 17.282 10.866)scale(1.7074)" gradientUnits="userSpaceOnUse"><stop class="zq34udb2s"/><stop offset="1" class="dnaxxhbrt"/></radialGradient><radialGradient id="ikAfObe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1.13227 13.357 10.448)" gradientUnits="userSpaceOnUse"><stop class="rxs_i_bcw"/><stop offset="1" class="x2oy13bqk"/></radialGradient><radialGradient id="iCxNa0c" cx="0" cy="0" r="1" gradientTransform="rotate(130.444 4.965 15.14)scale(1.0959 1.27055)" gradientUnits="userSpaceOnUse"><stop class="m2fhst2tl"/><stop offset="1" class="eqcd70b8h"/></radialGradient><radialGradient id="inuC9mc" cx="0" cy="0" r="1" gradientTransform="matrix(6.8452 -2.37754 2.63416 7.58403 2.847 26.732)" gradientUnits="userSpaceOnUse"><stop class="darzyxb2w"/><stop offset="1" class="tg3dr_b7j"/></radialGradient><linearGradient id="iAnIaPb" x1="18.416" x2="18.416" y1="14.737" y2="16.784" gradientUnits="userSpaceOnUse"><stop class="e8icacc3e"/><stop offset="1" class="zdv5nkr5d"/></linearGradient><linearGradient id="iCFWRMe" x1="18.416" x2="18.416" y1="16.784" y2="16.383" gradientUnits="userSpaceOnUse"><stop class="tssi88bwa"/><stop offset="1" class="ha9226bae"/></linearGradient><linearGradient id="ixqqWNF" x1="8.429" x2="8.429" y1="14.737" y2="18.761" gradientUnits="userSpaceOnUse"><stop class="zdgv0mpxr"/><stop offset="1" class="q4vh0vlwc"/></linearGradient><linearGradient id="inxfYAe" x1="24.607" x2="26.029" y1="27.331" y2="30.011" gradientUnits="userSpaceOnUse"><stop class="l5dzphbpk"/><stop offset="1" class="xbqnzpb-w"/></linearGradient><linearGradient id="iSjZ2wR" x1="27.732" x2="24.044" y1="28.979" y2="24.678" gradientUnits="userSpaceOnUse"><stop class="oxv4bniwv"/><stop offset=".391" class="yv4gq12qx"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="ixcdyed" x1="5.63" x2="7.052" y1="27.331" y2="30.011" gradientUnits="userSpaceOnUse"><stop class="l5dzphbpk"/><stop offset="1" class="xbqnzpb-w"/></linearGradient><linearGradient id="i5bwPXj" x1="8.955" x2="5.424" y1="28.979" y2="23.363" gradientUnits="userSpaceOnUse"><stop class="zmdd1yb-y"/><stop offset=".391" class="yv4gq12qx"/><stop offset=".692" class="f0k16nibb"/><stop offset="1" class="oeptinb4s"/></linearGradient><linearGradient id="iwUbZue" x1="11.451" x2="11.451" y1="9.714" y2="11.745" gradientUnits="userSpaceOnUse"><stop class="emaiwrajj"/><stop offset="1" class="uyvz-pwne"/></linearGradient><linearGradient id="iufOelb" x1="20.387" x2="29.07" y1="25.126" y2="21.905" gradientUnits="userSpaceOnUse"><stop class="xqvvlybbi"/><stop offset="1" class="zw8f-cc6e"/></linearGradient><filter id="ilezOub" width="20.691" height="17.938" x="7.923" y="9.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.231373 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11167"/></filter><filter id="iySr6Oe" width="6.505" height="6.505" x="22.14" y="24.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11167" stdDeviation=".2"/></filter><filter id="iIGIlNQ" width="2.936" height="2.936" x="4.798" y="26.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0862745 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_11167"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_11167" result="shape"/></filter><filter id="ibl58Fc" width="6.505" height="6.505" x="3.363" y="24.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11167" stdDeviation=".2"/></filter><filter id="iFFur5c" width="13.094" height="7.938" x="17.826" y="19.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.133333 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11167"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.396078 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11167" result="effect2_innerShadow_18_11167"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.121569 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_11167" result="effect3_innerShadow_18_11167"/></filter><filter id="ik8NsTc" width="10.717" height="4.755" x=".963" y="21.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.290196 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11167"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.341176 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11167" result="effect2_innerShadow_18_11167"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:motor-scooter" /></template>
<style>
.d_h9nrb1p {
  cx: 25.392px;
  cy: 27.331px;
  r: 2.652px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.darzyxb2w {
  stop-color: var(--svg-color--fd297d, #FD297D);
}

.dnaxxhbrt {
  stop-color: var(--svg-color--cdb0cc, #CDB0CC);
}

.e8icacc3e {
  stop-color: var(--svg-color--764d47, #764D47);
}

.eefp3crkp {
  cx: 6.415px;
  cy: 27.331px;
  r: 3.355px;
}

.emaiwrajj {
  stop-color: var(--svg-color--3f3b43, #3F3B43);
}

.eqcd70b8h {
  stop-color: var(--svg-color--a12a32, #A12A32);
  stop-opacity: 0;
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.fh6o-nbvu {
  stop-color: var(--svg-color--946663, #946663);
  stop-opacity: 0;
}

.fhn790bpu {
  d: path("M18.826 24.198a3.47 3.47 0 0 1 3.468-3.469h4.125a3.5 3.5 0 0 1 3.5 3.5v2.438a1 1 0 0 1-1 1h-6.625a3.47 3.47 0 0 1-3.468-3.469");
}

.ft5dv1b6b {
  fill: none;
}

.guza7pc9a {
  cx: 6.615px;
  cy: 27.331px;
  r: 2.652px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
}

.ha9226bae {
  stop-color: var(--svg-color--4d0d13, #4D0D13);
  stop-opacity: 0;
}

.k2aeny25u {
  cx: 25.392px;
  cy: 27.331px;
  r: 3.355px;
}

.l0kfffz0u {
  stop-color: var(--svg-color--ff399a, #FF399A);
}

.l2198zboi {
  stop-color: var(--svg-color--93505d, #93505D);
}

.l5dzphbpk {
  stop-color: var(--svg-color--341a5d, #341A5D);
}

.m-je2jb8l {
  stop-color: var(--svg-color--c52352, #C52352);
}

.m0qscobul {
  stop-color: var(--svg-color--c52352, #C52352);
  stop-opacity: 0;
}

.m2fhst2tl {
  stop-color: var(--svg-color--a12a32, #A12A32);
}

.m674nab1b {
  stop-color: var(--svg-color--946663, #946663);
}

.nmmi8v6ew {
  cx: 25.392px;
  cy: 27.331px;
  r: 1.168px;
  fill: var(--svg-color--dec0fb, #DEC0FB);
}

.nncn12fxv {
  d: path("M7.923 18.747v-3.996a.86.86 0 0 1 1.012.846V17.9a.86.86 0 0 1-1.012.846");
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.oxv4bniwv {
  stop-color: var(--svg-color--492c6e, #492C6E);
}

.plm1ecbru {
  cx: 6.415px;
  cy: 27.331px;
  r: 1.168px;
}

.q4vh0vlwc {
  stop-color: var(--svg-color--e2ac1c, #E2AC1C);
}

.qp_naeopl {
  stop-color: var(--svg-color--93505d, #93505D);
  stop-opacity: 0;
}

.r_5ts0szz {
  stop-color: var(--svg-color--fa3b4b, #FA3B4B);
}

.rf43v0b_j {
  width: 5.031px;
  height: 2.031px;
  x: 8.935px;
  y: 9.714px;
  rx: 1.016px;
}

.rxs_i_bcw {
  stop-color: var(--svg-color--565557, #565557);
}

.tg3dr_b7j {
  stop-color: var(--svg-color--ff435d, #FF435D);
}

.tssi88bwa {
  stop-color: var(--svg-color--4d0d13, #4D0D13);
}

.uyvz-pwne {
  stop-color: var(--svg-color--3f2456, #3F2456);
}

.x2oy13bqk {
  stop-color: var(--svg-color--565557, #565557);
  stop-opacity: 0;
}

.xbqnzpb-w {
  stop-color: var(--svg-color--4a1b77, #4A1B77);
}

.xl9f4fbyk {
  d: path("M7.923 11.73a2 2 0 0 1 2-2h2.012v13.468a.5.5 0 0 0 .5.5h4a1.484 1.484 0 0 0 0-2.969h-.62a1.895 1.895 0 0 1-1.896-1.894v-1.678c0-.219.178-.396.397-.396H24.71q.106-.008.216-.008a2.94 2.94 0 1 1-.1 5.877v2.568h-2.5a2.5 2.5 0 0 1-2.5 2.469H7.924z");
}

.xqvvlybbi {
  stop-color: var(--svg-color--d93871, #D93871);
}

.xtvruf4xi {
  d: path("M10.456 26.732c.264 0 .486-.207.473-.471c-.114-2.337-2.091-4.284-4.482-4.284s-4.368 1.947-4.483 4.284c-.013.264.209.47.474.47z");
}

.yscgurb3c {
  d: path("M13.966 16.428c0-.934.757-1.69 1.691-1.69h5.517c.934 0 1.69.756 1.69 1.69a.355.355 0 0 1-.355.356h-8.187a.356.356 0 0 1-.356-.356");
}

.yv4gq12qx {
  stop-color: var(--svg-color--492c6e, #492C6E);
  stop-opacity: 0;
}

.zdgv0mpxr {
  stop-color: var(--svg-color--eda42d, #EDA42D);
}

.zdv5nkr5d {
  stop-color: var(--svg-color--76344b, #76344B);
}

.zmdd1yb-y {
  stop-color: var(--svg-color--4e2f71, #4E2F71);
}

.zq34udb2s {
  stop-color: var(--svg-color--dabcf9, #DABCF9);
}

.zw8f-cc6e {
  stop-color: var(--svg-color--f64361, #F64361);
}

</style>
