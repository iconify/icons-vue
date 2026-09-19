<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i6Gnbyc)" class="lov8ucczh"/><path fill="url(#iEr7lqL)" class="fuc1futtc"/><g filter="url(#igfUbjK)"><rect fill="url(#iryLh1b)" transform="scale(-1 1)rotate(-45 -7.183 26.315)" class="md7m_7-2g"/></g><g filter="url(#iEQ6YUd)"><rect transform="rotate(-45 10.33 2.629)" class="hctqyqbik"/></g><g filter="url(#iMdONTc)"><path class="ljla4aczv"/></g><g filter="url(#iqCoHtb)"><path stroke="url(#icHjLgB)" class="eh9zshbpw"/></g><g filter="url(#iVBix9c)"><path fill="url(#i5mgFeS)" class="zvgz6un0f"/></g><g filter="url(#iIEJ1re)"><path stroke="url(#i6KSkEb)" clip-rule="evenodd" class="dedr3bbao"/><path stroke="url(#ir9Qabe)" clip-rule="evenodd" class="dedr3bbao"/></g><g filter="url(#ibCFPmb)"><rect fill="url(#ixJ9yDb)" class="azd36kb4u"/></g><g filter="url(#ii5JKQc)"><path fill="url(#iwnhI5x)" clip-rule="evenodd" class="bwuq9ojst"/></g><g filter="url(#izaIx3N)"><circle stroke="url(#iKUJJGe)" class="yn53acluy"/></g><g filter="url(#i8nOtPe)"><circle stroke="url(#i7Pms9z)" class="vibhyfjtj"/></g><circle fill="url(#ihtpLGd)" class="nh280mvol"/><circle fill="url(#iGizr0d)" class="ywatg1bmy"/><g filter="url(#iujc2Qn)"><circle class="a4llvtbct"/><circle fill="url(#imezTQd)" class="t2um67tzi"/></g><g filter="url(#i9QFMRc)"><circle class="hen37dvic"/><circle fill="url(#iAtQANc)" class="qkpjiab-v"/></g><g filter="url(#iaTMPoe)"><path fill="url(#i7Qwice)" class="u658deb0q"/></g><g filter="url(#i4Rtwjc)"><path fill="url(#iAiX7xj)" class="etwdidbac"/></g><defs><linearGradient id="i6Gnbyc" x1="8.593" x2="8.593" y1="24.609" y2="29.906" gradientUnits="userSpaceOnUse"><stop offset=".229" class="yfvc0hb9u"/><stop offset="1" class="slqj1zgot"/></linearGradient><linearGradient id="iEr7lqL" x1="24.804" x2="24.804" y1="24.609" y2="29.906" gradientUnits="userSpaceOnUse"><stop offset=".229" class="yfvc0hb9u"/><stop offset="1" class="slqj1zgot"/></linearGradient><linearGradient id="iryLh1b" x1=".468" x2=".468" y1="0" y2="8.397" gradientUnits="userSpaceOnUse"><stop class="jxtrqmq9q"/><stop offset=".619" class="sbpxsr-tw"/></linearGradient><linearGradient id="icHjLgB" x1="20.875" x2="18.906" y1="1.922" y2="3.719" gradientUnits="userSpaceOnUse"><stop class="r3ubp847i"/><stop offset="1" class="zc96crbse"/></linearGradient><linearGradient id="i5mgFeS" x1="16.484" x2="16.484" y1="6.141" y2="25.109" gradientUnits="userSpaceOnUse"><stop class="ankwt5vtt"/><stop offset="1" class="ut91amb8h"/></linearGradient><linearGradient id="i6KSkEb" x1="22.188" x2="14.914" y1="8.422" y2="18.221" gradientUnits="userSpaceOnUse"><stop class="go8zvqafw"/><stop offset="1" class="u_ma-bbtl"/></linearGradient><linearGradient id="ir9Qabe" x1="7.118" x2="16.153" y1="22.163" y2="12.71" gradientUnits="userSpaceOnUse"><stop class="syp-0fb7v"/><stop offset="1" class="m0t4-wbwm"/></linearGradient><linearGradient id="ixJ9yDb" x1="18.5" x2="11.675" y1="12.797" y2="20.035" gradientUnits="userSpaceOnUse"><stop class="tjp-afbdw"/><stop offset="1" class="zg4ycaciq"/></linearGradient><linearGradient id="iwnhI5x" x1="14.406" x2="24.313" y1="14.609" y2="20.141" gradientUnits="userSpaceOnUse"><stop class="kwwqqkbwf"/><stop offset=".564" class="ip5tb8bze"/></linearGradient><linearGradient id="iKUJJGe" x1="26.827" x2="25.432" y1="12.5" y2="14.646" gradientUnits="userSpaceOnUse"><stop class="iozoij0ms"/><stop offset="1" class="ucitpu8hr"/></linearGradient><linearGradient id="i7Pms9z" x1="27.094" x2="25.432" y1="8.461" y2="10.802" gradientUnits="userSpaceOnUse"><stop class="gpdazcbld"/><stop offset=".786" class="vwkg8bu_c"/></linearGradient><linearGradient id="ihtpLGd" x1="26.6" x2="26.164" y1="8.838" y2="10.617" gradientUnits="userSpaceOnUse"><stop offset=".055" class="khjbn1bxf"/><stop offset="1" class="e5y9x_6nl"/></linearGradient><linearGradient id="iGizr0d" x1="27.328" x2="25.85" y1="13.024" y2="14.245" gradientUnits="userSpaceOnUse"><stop offset=".222" class="uarqsgtbz"/><stop offset="1" class="xnqml60en"/></linearGradient><linearGradient id="i7Qwice" x1="8.214" x2="10" y1="29.016" y2="24.969" gradientUnits="userSpaceOnUse"><stop class="h2nfevmlm"/><stop offset="1" class="t8mcvjb5q"/></linearGradient><linearGradient id="iAiX7xj" x1="25.91" x2="23.969" y1="29.016" y2="24.203" gradientUnits="userSpaceOnUse"><stop class="g7jwfmpmt"/><stop offset="1" class="jfiuwu3nl"/></linearGradient><filter id="igfUbjK" width="6.212" height="6.462" x="14.305" y="1.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.501961 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20236"/></filter><filter id="iEQ6YUd" width="6.212" height="6.612" x="10.524" y="1.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.501961 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20236"/></filter><filter id="iMdONTc" width="4.628" height="4.628" x="10.772" y="2.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".075"/></filter><filter id="iqCoHtb" width="4.628" height="4.628" x="15.725" y="2.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".075"/></filter><filter id="iVBix9c" width="26.781" height="19.969" x="3.094" y="5.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.513726 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20236"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.67451 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20236" result="effect2_innerShadow_18_20236"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.823529 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_20236" result="effect3_innerShadow_18_20236"/></filter><filter id="iIEJ1re" width="19.078" height="15.938" x="5.375" y="7.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".25"/></filter><filter id="ibCFPmb" width="15.041" height="11.9" x="7.194" y="9.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.447059 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20236"/></filter><filter id="ii5JKQc" width="17.078" height="14.188" x="6.375" y="8.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.172549 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20236"/></filter><filter id="izaIx3N" width="3.456" height="3.456" x="24.522" y="11.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".2"/></filter><filter id="i8nOtPe" width="3.456" height="3.456" x="24.522" y="7.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".2"/></filter><filter id="iujc2Qn" width="2.055" height="2.055" x="25.222" y="8.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".125"/></filter><filter id="i9QFMRc" width="2.055" height="2.055" x="25.222" y="12.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".125"/></filter><filter id="iaTMPoe" width="2.967" height="4.305" x="7.027" y="25.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".2"/></filter><filter id="i4Rtwjc" width="3.155" height="4.49" x="23.959" y="25.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20236" stdDeviation=".2"/></filter><radialGradient id="imezTQd" cx="0" cy="0" r="1" gradientTransform="rotate(-33.69 29.035 -37.811)scale(1.25774)" gradientUnits="userSpaceOnUse"><stop offset=".588" class="q31uiz8nf"/><stop offset="1" class="u42ogib_s"/></radialGradient><radialGradient id="iAtQANc" cx="0" cy="0" r="1" gradientTransform="rotate(-33.69 35.383 -35.89)scale(1.25775)" gradientUnits="userSpaceOnUse"><stop offset=".588" class="pt9vqv-yy"/><stop offset="1" class="e7lusvb2u"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:television" /></template>
<style>
.a4llvtbct {
  cx: 26.25px;
  cy: 9.539px;
  r: 0.778px;
  fill: var(--svg-color--9d98a2, #9D98A2);
}

.ankwt5vtt {
  stop-color: var(--svg-color--b7b2bd, #B7B2BD);
}

.azd36kb4u {
  width: 14.641px;
  height: 11.5px;
  x: 7.594px;
  y: 9.641px;
  rx: 0.5px;
}

.bwuq9ojst {
  fill-rule: evenodd;
  d: path("M21.453 9.672H8.375a.75.75 0 0 0-.75.75v9.937c0 .415.336.75.75.75h13.078a.75.75 0 0 0 .75-.75v-9.937a.75.75 0 0 0-.75-.75M8.375 8.422a2 2 0 0 0-2 2v9.937a2 2 0 0 0 2 2h13.078a2 2 0 0 0 2-2v-9.937a2 2 0 0 0-2-2z");
}

.dedr3bbao {
  d: path("M8.375 8.422a2 2 0 0 0-2 2v9.937a2 2 0 0 0 2 2h13.078a2 2 0 0 0 2-2v-9.937a2 2 0 0 0-2-2z");
}

.e5y9x_6nl {
  stop-color: var(--svg-color--897a92, #897A92);
}

.e7lusvb2u {
  stop-color: var(--svg-color--ff5ea2, #FF5EA2);
}

.eh9zshbpw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.078 2.61L16 6.687");
}

.etwdidbac {
  d: path("M25.813 25.406h-1.454l1.675 3.487a.358.358 0 0 0 .667-.25z");
}

.ft5dv1b6b {
  fill: none;
}

.fuc1futtc {
  d: path("M25.757 24.172h-3.094l2.425 5.173a.974.974 0 0 0 1.826-.655z");
}

.g7jwfmpmt {
  stop-color: var(--svg-color--615571, #615571);
}

.go8zvqafw {
  stop-color: var(--svg-color--978ca7, #978CA7);
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.h2nfevmlm {
  stop-color: var(--svg-color--574769, #574769);
}

.hctqyqbik {
  width: 0.936px;
  height: 8.397px;
  x: 10.33px;
  y: 2.629px;
  fill: var(--svg-color--a3a2a4, #A3A2A4);
  rx: 0.468px;
}

.hen37dvic {
  cx: 26.25px;
  cy: 13.383px;
  r: 0.778px;
  fill: var(--svg-color--f43b76, #F43B76);
}

.iozoij0ms {
  stop-color: var(--svg-color--ac99a2, #AC99A2);
}

.ip5tb8bze {
  stop-color: var(--svg-color--554665, #554665);
}

.jfiuwu3nl {
  stop-color: var(--svg-color--615571, #615571);
  stop-opacity: 0;
}

.jxtrqmq9q {
  stop-color: var(--svg-color--a3a2a4, #A3A2A4);
}

.khjbn1bxf {
  stop-color: var(--svg-color--9f9da0, #9F9DA0);
}

.kwwqqkbwf {
  stop-color: var(--svg-color--403e43, #403E43);
}

.ljla4aczv {
  stroke: var(--svg-color--acaaae, #ACAAAE);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m11.047 2.516l4.078 4.078");
}

.lov8ucczh {
  d: path("M7.64 24.172h3.094L8.31 29.345a.974.974 0 0 1-1.827-.655z");
}

.m0t4-wbwm {
  stop-color: var(--svg-color--d0cbd6, #D0CBD6);
  stop-opacity: 0;
}

.md7m_7-2g {
  width: 0.936px;
  height: 8.397px;
  rx: 0.468px;
}

.nh280mvol {
  cx: 26.25px;
  cy: 9.539px;
  r: 1.078px;
}

.pt9vqv-yy {
  stop-color: var(--svg-color--ff5ea2, #FF5EA2);
  stop-opacity: 0;
}

.q31uiz8nf {
  stop-color: var(--svg-color--bcbabe, #BCBABE);
  stop-opacity: 0;
}

.qkpjiab-v {
  cx: 26.25px;
  cy: 13.383px;
  r: 0.778px;
}

.r3ubp847i {
  stop-color: var(--svg-color--b6b5b8, #B6B5B8);
}

.sbpxsr-tw {
  stop-color: var(--svg-color--929292, #929292);
}

.slqj1zgot {
  stop-color: var(--svg-color--5f3c80, #5F3C80);
}

.syp-0fb7v {
  stop-color: var(--svg-color--d0cbd6, #D0CBD6);
}

.t2um67tzi {
  cx: 26.25px;
  cy: 9.539px;
  r: 0.778px;
}

.t8mcvjb5q {
  stop-color: var(--svg-color--574769, #574769);
  stop-opacity: 0;
}

.tjp-afbdw {
  stop-color: var(--svg-color--5bd5fe, #5BD5FE);
}

.u_ma-bbtl {
  stop-color: var(--svg-color--978ca7, #978CA7);
  stop-opacity: 0;
}

.u42ogib_s {
  stop-color: var(--svg-color--bcbabe, #BCBABE);
}

.u658deb0q {
  d: path("M8.546 25.594h1.048l-1.515 3.305a.342.342 0 0 1-.632-.258z");
}

.uarqsgtbz {
  stop-color: var(--svg-color--ff56a4, #FF56A4);
}

.ucitpu8hr {
  stop-color: var(--svg-color--a090a0, #A090A0);
}

.ut91amb8h {
  stop-color: var(--svg-color--bab1c4, #BAB1C4);
}

.vibhyfjtj {
  cx: 26.25px;
  cy: 9.539px;
  r: 1.078px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.vwkg8bu_c {
  stop-color: var(--svg-color--98919f, #98919F);
}

.xnqml60en {
  stop-color: var(--svg-color--c4294f, #C4294F);
}

.yfvc0hb9u {
  stop-color: var(--svg-color--30273c, #30273C);
}

.yn53acluy {
  cx: 26.25px;
  cy: 13.383px;
  r: 1.078px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.ywatg1bmy {
  cx: 26.25px;
  cy: 13.383px;
  r: 1.078px;
}

.zc96crbse {
  stop-color: var(--svg-color--b6b5b8, #B6B5B8);
  stop-opacity: 0;
}

.zg4ycaciq {
  stop-color: var(--svg-color--37a2df, #37A2DF);
}

.zvgz6un0f {
  d: path("M3.594 8.39a2.25 2.25 0 0 1 2.25-2.25h21.281a2.25 2.25 0 0 1 2.25 2.25v14.47a2.25 2.25 0 0 1-2.25 2.25H5.844a2.25 2.25 0 0 1-2.25-2.25z");
}

</style>
